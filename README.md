# Polars-with-hvPlot-learning
Polarsにグラフ描画メソッドを組み込むことができるライブラリhvPlotの練習リポジトリ.

文章の多くは,Google翻訳を使用しています.

## Reference Gallery
各節のリンクはhvPlotのWebページ
1. Tabular
1. Geopandas
1. Xarray
    1. [Bar](https://hvplot.holoviz.org/reference/xarray/bar.html)
        * xarrayのチュートリアルデータを使って棒グラフを描画します.
        * Polarsデータフレームをインスタンス化する時に,[xarray.DataArray.to_dataframe](https://docs.xarray.dev/en/latest/generated/xarray.DataArray.to_dataframe.html)で一度Pandasデータフレームに変換してから,[polars.from_pandas](https://docs.pola.rs/py-polars/html/reference/api/polars.from_pandas.html)で読み込んでいます.



## 参考URL
* [hvPlot — hvPlot 0.9.2 documentation](https://hvplot.holoviz.org/index.html)

