# Signal and System Dr. Ghasemian plots with Jupyter

![banner of project](assets/banner.png)

This project contains Jupyter notebooks for plotting various signals commonly used in signal processing and universities courses.

## Usage ⚙️

- Each Jupyter notebook in this project corresponds to a specific type of signal. You can open and run these notebooks to generate plots for different signals.
- I wrote my codes in [VsCode](https://code.visualstudio.com/) so I recommend you to open Jupyter files with it too.
- I did not wrote plt.show(), so you can add it in last line of all Jupyter files if needed!
- Please before run Jupyter codes, with pip install numpy and matplotlib in your terminal:

  ```bash
  pip install numpy
  pip install matplotlib
  ```

### Design Hints 🎨

- I used red color for signals by putting 'r' in plot function so you can remove or change this value:

```python
plt.stem(n, y, 'r', basefmt=' ')
```

- If you do not like black background in signal plots you can remove this code in all .ipynb files

```python
plt.style.use("dark_background")
```

## Contributing 👍

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## Credits 🧑‍🏫📚

- Some signal snippets were adapted from the book "Signals and Systems by Oppenheim and Willsky"
- All plot codes was inspired by the examples in the matplotlib documentation in Dr.Ghasemian powerpoint.
