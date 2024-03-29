# TeaScapes
A tea cropland benchmark for geographical domain shifts. 

TeaScapes focuses on the tea cropland recognition task in different sites with diverse topographic features and tea crop types. The images are selected from Fujian province which is a tea planting base in China. In Fujian province, Anxi county in the hilly area, Wuyishan county in mountain area and Fuding city in coastal zoo are with higher yields of the tea crop. Diverse tea crop types are planted. In addtion, these sites are with different tea crop types. Anxi county mainly cultivates the Tieguanyin and Maoxie tea crops, Wuyishan county mainly plants the tea crops of the Jinjunmei and Zhengshanxiaozhong, and Fuding city mainly plants the Gongmei and Baihaoyinzhen tea crops. As a result, there are apparent domain shifts in these areas. 

As the tea cropland recognition orients to large-scale applications, very high resolution remote sensing images are not necessary. We select the remote sensing images with 10m resolution. To facilitate the recognition, users usually obtain the reomte sensing images on Google Earth for convenience. Therefore, we use the remote sensing images on Google Earth as the data source for the sake of application limits. The three areas including Anxi county, Wuyishan county, and Fuding city are dividied by image tiles with $2000\times 2000$ pixels. The cut-off lines of this division which ensures 200 pixels overlaps between adjacent image tiles are shown in Fig.~\ref{Fig_teascapes}. After the division, there are 360, 225, and 234 image tiles in Anxi county, Wuyishan county and Fuding city, respectively. These image tiles in the three groups construct the TeaScapes. 


The benchmark will be published when the paper is accepted. 

