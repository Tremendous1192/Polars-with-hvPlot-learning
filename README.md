# Polars-with-hvPlot-learning
Polarsにグラフ描画メソッドを組み込むことができるライブラリhvPlotの練習リポジトリ.

文章の多くは,Google翻訳を使用しています.

## Reference Gallery
各節のリンクはhvPlotのWebページ
1. Tabular
    1. [Andrewscurves](https://hvplot.holoviz.org/reference/tabular/andrewscurves.html)
        * 2024年4月9日時点でPolars未対応
    1. [Area](https://hvplot.holoviz.org/reference/tabular/area.html)
        * 2つの曲線の間を塗りつぶす方法
    1. [Bar](https://hvplot.holoviz.org/reference/tabular/bar.html)
        * 通常の棒グラフと積み上げ棒グラフ
    1. [Barh](https://hvplot.holoviz.org/reference/tabular/barh.html)
        * 水平方向の棒グラフと```by```キーワードで色分けする方法
    1. [Bivariate](https://hvplot.holoviz.org/reference/tabular/bivariate.html)
        * 二次元密度分布
    1. [Box](https://hvplot.holoviz.org/reference/tabular/box.html)
        * 箱ひげ図
    1. [Errorbars](https://hvplot.holoviz.org/reference/tabular/errorbars.html)
        * ```*```演算子で既存の散布図にエラーバーを追加する方法
    1. [Heatmap](https://hvplot.holoviz.org/reference/tabular/heatmap.html)
        * 2024年4月12日時点でPolars未対応
    1. [Hexbin](https://hvplot.holoviz.org/reference/tabular/hexbin.html)
        * サンプルデータセットを取得できなかった
    1. [Hist](https://hvplot.holoviz.org/reference/tabular/hist.html)
        * ヒストグラム
    1. [Kde](https://hvplot.holoviz.org/reference/tabular/kde.html)
        * 1次元密度分布
    1. [Labels](https://hvplot.holoviz.org/reference/tabular/labels.html)
        * グラフへのラベル追加
    1. [Lagplot](https://hvplot.holoviz.org/reference/tabular/lagplot.html)
       * 2024年4月12日時点でPolars未対応
    1. [Line](https://hvplot.holoviz.org/reference/tabular/line.html)
       * 折れ線グラフ
    1. [Ohlc](https://hvplot.holoviz.org/reference/tabular/ohlc.html)
       * ローソク足
       * グラフを縦にまとめる方法
    1. [Parallelcoordinates](https://hvplot.holoviz.org/reference/tabular/parallelcoordinates.html)
       * 2024年4月12日時点でPolars未対応
    1. [Scatter](https://hvplot.holoviz.org/reference/tabular/scatter.html)
       * 散布図
1. Geopandas
1. Xarray
    1. [Bar](https://hvplot.holoviz.org/reference/xarray/bar.html)
        * xarrayのチュートリアルデータを使って棒グラフを描画します.
        * Polarsデータフレームをインスタンス化する時に,[xarray.DataArray.to_dataframe](https://docs.xarray.dev/en/latest/generated/xarray.DataArray.to_dataframe.html)で一度Pandasデータフレームに変換してから,[polars.from_pandas](https://docs.pola.rs/py-polars/html/reference/api/polars.from_pandas.html)で読み込んでいます.
    1. [Contour](https://hvplot.holoviz.org/reference/xarray/contour.html)
        * 2024年4月9日時点ではPolarsで等高線を描画できませんでした.



## 参考URL
* [hvPlot — hvPlot 0.9.2 documentation](https://hvplot.holoviz.org/index.html)

