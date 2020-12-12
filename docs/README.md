# Documentation

## Creating a Progressbar
You can eather create a progressbar through the Designer or through code.

### Using the Designer
You can simply drag and drop the Progressbar onto your Form using the toolbox shipped wtih Visual Studio.

### Using code
If you want tó create your Progressbar through code, you simply specify a new variable of the type `Matix.Controls.Progressbar.ProgressBar`.

```cs
Matix.Controls.Progressbar.ProgressBar progressbar = new Matix.Controls.Progressbar.ProgressBar();
```

Or if you want to shorten the Assembly name, you just specify a new `using term`.

```cs
using Matix.Controls;
```

and then simply create the progressbar like this

```cs
Progressbar.ProgressBar progressbar = new Progressbar.ProgressBar();
```

## Properties
The Progressbar has multiple customizable properties.

### Flat
The property `Flat` defines if the Progressbar should be Flat or not.  
`Flat` on:  
![Flat Progressbar](https://imgur.com/3TDYsjE.png)

`Flat` off:  
![3D Border Progressbar](https://imgur.com/1o3AFhS.png)

### BackColor
With the `BackColor` property, you can customize the background color of the progessbar.  
`BackColor` set to `Black`:  
![BackColor set to black](https://imgur.com/hiR7lkz.png)

`BackColor` set to `Green`:  
![BackColor set to green](https://imgur.com/Xz7kSFX.png)

### ForeColor
The `ForeColor` property defines the color of the progressbar which displays the value.
`ForeColor` set to `Blue`:  
![ForeColor set to blue](https://imgur.com/DXSktmz.png)

`ForeColor` set to `Yellow`:  
![ForeColor set to yellow](https://imgur.com/MPKnVTT.png)

### Maximum
The property `Maximum` defines the maximum value of the progressbar.

### Minimum
`Minimum` sets the minimum value of the progressbar.

### Value
The `Value` property defines the current value of the progressbar.
