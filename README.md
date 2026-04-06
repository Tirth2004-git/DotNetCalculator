# Calc_DotNet

A simple desktop calculator built with C# and Windows Forms (.NET Framework 4.7.2).

## Project Overview

This project is a basic calculator application with a graphical interface.
It supports the main arithmetic operations and includes division-by-zero protection.

## Features

- Number input (0-9)
- Arithmetic operations: `+`, `-`, `*`, `/`
- Equals (`=`) to compute results
- Clear (`C`) button to reset input
- Message alert when attempting division by zero

## Tech Stack

- Language: C#
- UI Framework: Windows Forms
- Target Framework: .NET Framework 4.7.2
- IDE: Visual Studio (recommended)

## Project Structure

```text
Calc_DotNet-main/
	README.md
	CalculatorApp/
		CalculatorApp.sln
		CalculatorApp/
			Program.cs
			Form1.cs
			Form1.Designer.cs
			CalculatorApp.csproj
```

## How To Run

### Option 1: Visual Studio (Recommended)

1. Open `CalculatorApp/CalculatorApp.sln` in Visual Studio.
2. Build the solution.
3. Press `F5` to run.

### Option 2: Run Existing Debug Build

If already built, run:

```powershell
CalculatorApp/CalculatorApp/bin/Debug/CalculatorApp.exe
```
