# Custom JupyterLite Environment

```bash
% cd content 
% ls
data			p5.ipynb		python.ipynb
javascript.ipynb	pyodide
% git rm *ipynb
rm 'content/javascript.ipynb'
rm 'content/p5.ipynb'
rm 'content/python.ipynb'
(base) rpwagner@Corsair content % cd da
(base) rpwagner@Corsair content % git rm -rf pyodide 
rm 'content/pyodide/altair.ipynb'
rm 'content/pyodide/folium.ipynb'
rm 'content/pyodide/interactive-widgets.ipynb'
rm 'content/pyodide/ipycanvas.ipynb'
rm 'content/pyodide/ipyleaflet.ipynb'
rm 'content/pyodide/matplotlib.ipynb'
rm 'content/pyodide/plotly.ipynb'
rm 'content/pyodide/pyb2d/0_tutorial.ipynb'
rm 'content/pyodide/pyb2d/color_mixing.ipynb'
rm 'content/pyodide/pyb2d/games/angry_shapes.ipynb'
rm 'content/pyodide/pyb2d/games/billiard.ipynb'
rm 'content/pyodide/pyb2d/games/goo.ipynb'
rm 'content/pyodide/pyb2d/games/rocket.ipynb'
rm 'content/pyodide/pyb2d/gauss_machine.ipynb'
rm 'content/pyodide/pyb2d/newtons_cradle.ipynb'
rm 'content/pyodide/renderers.ipynb'
(base) rpwagner@Corsair content %% git rm data/*
rm 'content/data/Museums_in_DC.geojson'
rm 'content/data/bar.vl.json'
rm 'content/data/fasta-example.fasta'
rm 'content/data/iris.csv'
rm 'content/data/matplotlib.png'
{
  "jupyter-lite-schema-version": 0,
  "jupyter-config-data": {
    "litePluginSettings": {
      "@jupyterlite/pyodide-kernel-extension:kernel": {
        "pyodideUrl": "https://rickwagner.io/pyodide-ext/pyodide.js"
      }
    }
  }
}
```

