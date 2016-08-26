# QHCityCollectionView-2016
===========================

# 2016年7月最新三级城市CollectionView选择器
------------------

## `Show`
![](https://github.com/guodongZhao/ZGDDatePicker-Tool/raw/master/testShow.gif)

### 


### `Method`
```objc
```


#### `Delegate 回调`
```objc 
/**
 *
 *
 *  @param cityCollectionView CityCollectionView
 *  @param proviceName        一级省份名称
 *  @param proviceID          一级省份ID
 *  @param cityName           二级城市名称
 *  @param cityID             二级城市ID
 *  @param areaName           三级地区名称
 *  @param areaID             三级地区ID
 *  @param page               当前页数
 */
-(void)CityCollectionView:(CityCollectionView *)cityCollectionView ProviceName:(NSString *)proviceName ProviceID:(NSString *)proviceID CityName:(NSString*)cityName CityID:(NSString *)cityID AreaName:(NSString *)areaName AreaID:(NSString *)areaID Page:(NSInteger)page;
```
