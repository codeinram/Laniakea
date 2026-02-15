# Laniakea is a continuation on Q17
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; max-width: 800px; margin: 40px auto; padding: 20px; }
        h2 { font-size: 1.4em; margin-top: 2em; }
        p { margin-bottom: 1em; }
        ul { padding-left: 20px; }
        li { margin-bottom: 0.8em; }
    </style>
</head>
<body>

<p>The aim is to offer a highly musical design using available parts.</p>

<p>Laniakea keeps the core of feed-forward error correction while adding state-of-the-art audio engineering design. The design combines the best from power lateral MOSFETs with vertical MOSFETs while using depletion MOSFETs as regulators and for small-signal applications.</p>

<h2>What Has Been Added and Changed</h2>

<ul>
    <li>The operational amplifier has been changed to ADA4610-1.</li>
    <li>UF3N170400B7S together with DN2540 form a particular cascode. The UF3N170400B7S is a JFET with a low threshold voltage (Vth &lt; -9 V) and runs the DN2540 in a linear region at a decent Vds.</li>
    <li>The output stage is a mix of lateral and vertical MOSFETs, combining the linearity of lateral MOSFETs with the high transconductance of vertical MOSFETs.</li>
</ul>

</body>
</html>

--- under construction ---

Schematic:
![laniakea](https://github.com/user-attachments/assets/7b599a17-0707-42d4-ad4b-1652ddded7f8)
