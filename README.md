# 検量線
濃度既知の溶液複数を用意し，検量線を測定する．得られたデータを元に直線近似を行って回帰線，回帰式を求める．近似線が高濃度で曲がるようであればその濃度を外す．

# サンプル
サンプルの初期濃度，サンプルの体積，LDHの質量，吸着後の吸光度を測定する．
サンプルの吸光度を測定し，検量線の回帰式から濃度を推定する．濃度から以下を求める．

$$吸着率 = (1-吸着濃度/初期濃度)\times 100$$

$$吸着量[\textrm{g/g\cdot LDH}] = (吸着率)/100 \times (初期濃度)\times(体積)/(LDH質量)$$

データをExcelにまとめる際は一つのサンプルにつき一行にまとめ，列を下にコピーするとよい．
