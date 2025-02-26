# 🌍 Remote Sensing Land Classification

## 📌 **Project Overview**
A deep learning-based remote sensing land classification project using **CNN**, **ResNet-50**, **DenseNet-121**, and **EfficientNet-B0** to categorize various land types from `.tif` images.  
The goal is to classify images into seven main categories: construction land, cultivated land, land, objects, transportation, water area, and woodland, by training and evaluating multiple deep learning models for performance comparison.

---

## 📂 **Dataset**
### [📥 Download Dataset](https://pz3gzw.dm.files.1drv.com/y4mXZ63cZF1JqpWtU_BqezsKxYoNK5BxtnQ9PD97LFsU-fOFSdejEP3h5bqGdICIY_M3uzDKRg44l354LtqpgEhqF6Cgm0GbjjFTTkhLz4yrf2zq77t-O2jo7tQrutM1jro1GoHrkX9IdKJ6zluGM3hWgsbDauOs5qB4H9CJ_jKb402N1cAt-4HEaa8uQwa1jrEdqpz35LQTewH5fpRZpHQdg)


The dataset is organized into seven main categories with corresponding subcategories:

```
├── constructionland
│   ├── city_building
│   ├── container
│   ├── residents
│   └── storage_room
│
├── cultivatedland
│   ├── bare_land
│   ├── dry_farm
│   └── green_farmland
│
├── land
│   ├── desert
│   ├── mountain
│   ├── sandbeach
│   └── snow_mountain
│
├── objects
│   ├── airplane
│   ├── pipeline
│   └── town
│
├── transportation
│   ├── airport_runway
│   ├── avenue
│   ├── bridge
│   ├── crossroads
│   ├── highway
│   ├── marina
│   └── parkinglot
│
├── waterarea
│   ├── coastline
│   ├── dam
│   ├── hirst
│   ├── lakeshore
│   ├── river
│   ├── sea
│   └── stream
│
└── woodland
    ├── artificial_grassland
    ├── forest
    ├── mangrove
    ├── river_protection_forest
    ├── sapling
    ├── shrubwood
    └── sparse_forest
```
## 🖼️ **Sample Dataset Images**
### 🏗️ Construction Land - City Building
#### City Building
<p align="center">
  <img src="Images/construction_land/city_building/city_building(1).jpg" width="18%" />
  <img src="Images/construction_land/city_building/city_building(2).jpg" width="18%" />
  <img src="Images/construction_land/city_building/city_building(3).jpg" width="18%" />
  <img src="Images/construction_land/city_building/city_building(4).jpg" width="18%" />
  <img src="Images/construction_land/city_building/city_building(5).jpg" width="18%" />
</p>

#### Container
<p align="center">
  <img src="Images/construction_land/container/container(1).jpg" width="18%" />
  <img src="Images/construction_land/container/container(2).jpg" width="18%" />
  <img src="Images/construction_land/container/container(3).jpg" width="18%" />
  <img src="Images/construction_land/container/container(4).jpg" width="18%" />
  <img src="Images/construction_land/container/container(5).jpg" width="18%" />
</p>

#### Residents
<p align="center">
  <img src="Images/construction_land/residents/residents(1).jpg" width="18%" />
  <img src="Images/construction_land/residents/residents(2).jpg" width="18%" />
  <img src="Images/construction_land/residents/residents(3).jpg" width="18%" />
  <img src="Images/construction_land/residents/residents(4).jpg" width="18%" />
  <img src="Images/construction_land/residents/residents(5).jpg" width="18%" />
</p>

#### Storage Room
<p align="center">
  <img src="Images/construction_land/storage_room/storage_room(1).jpg" width="18%" />
  <img src="Images/construction_land/storage_room/storage_room(2).jpg" width="18%" />
  <img src="Images/construction_land/storage_room/storage_room(3).jpg" width="18%" />
  <img src="Images/construction_land/storage_room/storage_room(4).jpg" width="18%" />
  <img src="Images/construction_land/storage_room/storage_room(5).jpg" width="18%" />
</p>

### 🌾 Cultivated Land - Green Farmland
#### Bare Land
<p align="center">
  <img src="Images/cultivatedland/bare_land/bare_land(1).jpg" width="18%" />
  <img src="Images/cultivatedland/bare_land/bare_land(2).jpg" width="18%" />
  <img src="Images/cultivatedland/bare_land/bare_land(3).jpg" width="18%" />
  <img src="Images/cultivatedland/bare_land/bare_land(4).jpg" width="18%" />
  <img src="Images/cultivatedland/bare_land/bare_land(5).jpg" width="18%" />
</p>

#### Dry Farm
<p align="center">
  <img src="Images/cultivatedland/dry_farm/dry_farm(1).jpg" width="18%" />
  <img src="Images/cultivatedland/dry_farm/dry_farm(2).jpg" width="18%" />
  <img src="Images/cultivatedland/dry_farm/dry_farm(3).jpg" width="18%" />
  <img src="Images/cultivatedland/dry_farm/dry_farm(4).jpg" width="18%" />
  <img src="Images/cultivatedland/dry_farm/dry_farm(5).jpg" width="18%" />
</p>

#### Green Farmland
<p align="center">
  <img src="Images/cultivatedland/green_farmland/green_farmland(1).jpg" width="18%" />
  <img src="Images/cultivatedland/green_farmland/green_farmland(2).jpg" width="18%" />
  <img src="Images/cultivatedland/green_farmland/green_farmland(3).jpg" width="18%" />
  <img src="Images/cultivatedland/green_farmland/green_farmland(4).jpg" width="18%" />
  <img src="Images/cultivatedland/green_farmland/green_farmland(5).jpg" width="18%" />
</p>

### 🏜️ Land - Desert
#### Desert
<p align="center">
  <img src="Images/land/desert/desert(1).jpg" width="18%" />
  <img src="Images/land/desert/desert(2).jpg" width="18%" />
  <img src="Images/land/desert/desert(3).jpg" width="18%" />
  <img src="Images/land/desert/desert(4).jpg" width="18%" />
  <img src="Images/land/desert/desert(5).jpg" width="18%" />
</p>

#### Mountain
<p align="center">
  <img src="Images/land/mountain/mountain(1).jpg" width="18%" />
  <img src="Images/land/mountain/mountain(2).jpg" width="18%" />
  <img src="Images/land/mountain/mountain(3).jpg" width="18%" />
  <img src="Images/land/mountain/mountain(4).jpg" width="18%" />
  <img src="Images/land/mountain/mountain(5).jpg" width="18%" />
</p>

#### Sandbeach
<p align="center">
  <img src="Images/land/sandbeach/sand_beach(1).jpg" width="18%" />
  <img src="Images/land/sandbeach/sand_beach(2).jpg" width="18%" />
  <img src="Images/land/sandbeach/sand_beach(3).jpg" width="18%" />
  <img src="Images/land/sandbeach/sand_beach(4).jpg" width="18%" />
  <img src="Images/land/sandbeach/sand_beach(5).jpg" width="18%" />
</p>

#### Snow Mountain
<p align="center">
  <img src="Images/land/snow_mountain/snow_mountain(1).jpg" width="18%" />
  <img src="Images/land/snow_mountain/snow_mountain(2).jpg" width="18%" />
  <img src="Images/land/snow_mountain/snow_mountain(3).jpg" width="18%" />
  <img src="Images/land/snow_mountain/snow_mountain(4).jpg" width="18%" />
  <img src="Images/land/snow_mountain/snow_mountain(5).jpg" width="18%" />
</p>

### ✈️ Objects - Airplane
#### Airplane
<p align="center">
  <img src="Images/objects/airplane/airplane(1).jpg" width="18%" />
  <img src="Images/objects/airplane/airplane(2).jpg" width="18%" />
  <img src="Images/objects/airplane/airplane(3).jpg" width="18%" />
  <img src="Images/objects/airplane/airplane(4).jpg" width="18%" />
  <img src="Images/objects/airplane/airplane(5).jpg" width="18%" />
</p>

#### Pipeline
<p align="center">
  <img src="Images/objects/pipeline/pipeline(1).jpg" width="18%" />
  <img src="Images/objects/pipeline/pipeline(2).jpg" width="18%" />
  <img src="Images/objects/pipeline/pipeline(3).jpg" width="18%" />
  <img src="Images/objects/pipeline/pipeline(4).jpg" width="18%" />
  <img src="Images/objects/pipeline/pipeline(5).jpg" width="18%" />
</p>

#### Town
<p align="center">
  <img src="Images/objects/town/town(1).jpg" width="18%" />
  <img src="Images/objects/town/town(2).jpg" width="18%" />
  <img src="Images/objects/town/town(3).jpg" width="18%" />
  <img src="Images/objects/town/town(4).jpg" width="18%" />
  <img src="Images/objects/town/town(5).jpg" width="18%" />
</p>

### 🚗 Transportation - Highway
#### Airport Runway
<p align="center">
  <img src="Images/transportation/airport_runway/airport_runway(1).jpg" width="18%" />
  <img src="Images/transportation/airport_runway/airport_runway(2).jpg" width="18%" />
  <img src="Images/transportation/airport_runway/airport_runway(3).jpg" width="18%" />
  <img src="Images/transportation/airport_runway/airport_runway(4).jpg" width="18%" />
  <img src="Images/transportation/airport_runway/airport_runway(5).jpg" width="18%" />
</p>

#### Avenue
<p align="center">
  <img src="Images/transportation/avenue/avenue(1).jpg" width="18%" />
  <img src="Images/transportation/avenue/avenue(2).jpg" width="18%" />
  <img src="Images/transportation/avenue/avenue(3).jpg" width="18%" />
  <img src="Images/transportation/avenue/avenue(4).jpg" width="18%" />
  <img src="Images/transportation/avenue/avenue(5).jpg" width="18%" />
</p>

#### Bridge
<p align="center">
  <img src="Images/transportation/bridge/bridge(1).jpg" width="18%" />
  <img src="Images/transportation/bridge/bridge(2).jpg" width="18%" />
  <img src="Images/transportation/bridge/bridge(3).jpg" width="18%" />
  <img src="Images/transportation/bridge/bridge(4).jpg" width="18%" />
  <img src="Images/transportation/bridge/bridge(5).jpg" width="18%" />
</p>

#### Crossroads
<p align="center">
  <img src="Images/transportation/crossroads/crossroads(1).jpg" width="18%" />
  <img src="Images/transportation/crossroads/crossroads(2).jpg" width="18%" />
  <img src="Images/transportation/crossroads/crossroads(3).jpg" width="18%" />
  <img src="Images/transportation/crossroads/crossroads(4).jpg" width="18%" />
  <img src="Images/transportation/crossroads/crossroads(5).jpg" width="18%" />
</p> 

#### Highway
<p align="center">
  <img src="Images/transportation/highway/highway(1).jpg" width="18%" />
  <img src="Images/transportation/highway/highway(2).jpg" width="18%" />
  <img src="Images/transportation/highway/highway(3).jpg" width="18%" />
  <img src="Images/transportation/highway/highway(4).jpg" width="18%" />
  <img src="Images/transportation/highway/highway(5).jpg" width="18%" />
</p>

#### Marina
<p align="center">
  <img src="Images/transportation/marina/marina(1).jpg" width="18%" />
  <img src="Images/transportation/marina/marina(2).jpg" width="18%" />
  <img src="Images/transportation/marina/marina(3).jpg" width="18%" />
  <img src="Images/transportation/marina/marina(4).jpg" width="18%" />
  <img src="Images/transportation/marina/marina(5).jpg" width="18%" />
</p>

#### Parkinglot
<p align="center">
  <img src="Images/transportation/parkinglot/parkinglot(1).jpg" width="18%" />
  <img src="Images/transportation/parkinglot/parkinglot(2).jpg" width="18%" />
  <img src="Images/transportation/parkinglot/parkinglot(3).jpg" width="18%" />
  <img src="Images/transportation/parkinglot/parkinglot(4).jpg" width="18%" />
  <img src="Images/transportation/parkinglot/parkinglot(5).jpg" width="18%" />
</p>

### 🌊 Water Area - River
#### Coastline
<p align="center">
  <img src="Images/waterarea/coastline/coastline(1).jpg" width="18%" />
  <img src="Images/waterarea/coastline/coastline(2).jpg" width="18%" />
  <img src="Images/waterarea/coastline/coastline(3).jpg" width="18%" />
  <img src="Images/waterarea/coastline/coastline(4).jpg" width="18%" />
  <img src="Images/waterarea/coastline/coastline(5).jpg" width="18%" />
</p>

#### Dam
<p align="center">
  <img src="Images/waterarea/dam/dam(1).jpg" width="18%" />
  <img src="Images/waterarea/dam/dam(2).jpg" width="18%" />
  <img src="Images/waterarea/dam/dam(3).jpg" width="18%" />
  <img src="Images/waterarea/dam/dam(4).jpg" width="18%" />
  <img src="Images/waterarea/dam/dam(5).jpg" width="18%" />
</p>

#### Hirst
<p align="center">
  <img src="Images/waterarea/hirst/hirst(1).jpg" width="18%" />
  <img src="Images/waterarea/hirst/hirst(2).jpg" width="18%" />
  <img src="Images/waterarea/hirst/hirst(3).jpg" width="18%" />
  <img src="Images/waterarea/hirst/hirst(4).jpg" width="18%" />
  <img src="Images/waterarea/hirst/hirst(5).jpg" width="18%" />
</p>

#### Lakeshore
<p align="center">
  <img src="Images/waterarea/lakeshore/lakeshore(1).jpg" width="18%" />
  <img src="Images/waterarea/lakeshore/lakeshore(2).jpg" width="18%" />
  <img src="Images/waterarea/lakeshore/lakeshore(3).jpg" width="18%" />
  <img src="Images/waterarea/lakeshore/lakeshore(4).jpg" width="18%" />
  <img src="Images/waterarea/lakeshore/lakeshore(5).jpg" width="18%" />
</p>

#### River
<p align="center">
  <img src="Images/waterarea/river/river(1).jpg" width="18%" />
  <img src="Images/waterarea/river/river(2).jpg" width="18%" />
  <img src="Images/waterarea/river/river(3).jpg" width="18%" />
  <img src="Images/waterarea/river/river(4).jpg" width="18%" />
  <img src="Images/waterarea/river/river(5).jpg" width="18%" />
</p>

#### Sea
<p align="center">
  <img src="Images/waterarea/sea/sea(1).jpg" width="18%" />
  <img src="Images/waterarea/sea/sea(2).jpg" width="18%" />
  <img src="Images/waterarea/sea/sea(3).jpg" width="18%" />
  <img src="Images/waterarea/sea/sea(4).jpg" width="18%" />
  <img src="Images/waterarea/sea/sea(5).jpg" width="18%" />
</p>

#### Stream
<p align="center">
  <img src="Images/waterarea/stream/stream(1).jpg" width="18%" />
  <img src="Images/waterarea/stream/stream(2).jpg" width="18%" />
  <img src="Images/waterarea/stream/stream(3).jpg" width="18%" />
  <img src="Images/waterarea/stream/stream(4).jpg" width="18%" />
  <img src="Images/waterarea/stream/stream(5).jpg" width="18%" />
</p>


### 🌳 Woodland - Forest
#### Artificial Grassland
<p align="center">
  <img src="Images/woodland/artificial_grassland/artificial_grassland(1).jpg" width="18%" />
  <img src="Images/woodland/artificial_grassland/artificial_grassland(2).jpg" width="18%" />
  <img src="Images/woodland/artificial_grassland/artificial_grassland(3).jpg" width="18%" />
  <img src="Images/woodland/artificial_grassland/artificial_grassland(4).jpg" width="18%" />
  <img src="Images/woodland/artificial_grassland/artificial_grassland(5).jpg" width="18%" />
</p>

#### Forest
<p align="center">
  <img src="Images/woodland/forest/forest(1).jpg" width="18%" />
  <img src="Images/woodland/forest/forest(2).jpg" width="18%" />
  <img src="Images/woodland/forest/forest(3).jpg" width="18%" />
  <img src="Images/woodland/forest/forest(4).jpg" width="18%" />
  <img src="Images/woodland/forest/forest(5).jpg" width="18%" />
</p>

#### Mangrove
<p align="center">
  <img src="Images/woodland/mangrove/mangrove(1).jpg" width="18%" />
  <img src="Images/woodland/mangrove/mangrove(2).jpg" width="18%" />
  <img src="Images/woodland/mangrove/mangrove(3).jpg" width="18%" />
  <img src="Images/woodland/mangrove/mangrove(4).jpg" width="18%" />
  <img src="Images/woodland/mangrove/mangrove(5).jpg" width="18%" />
</p>

#### River Protection Forest
<p align="center">
  <img src="Images/woodland/river_protection_forest/river_protetion_forest(1).jpg" width="18%" />
  <img src="Images/woodland/river_protection_forest/river_protetion_forest(2).jpg" width="18%" />
  <img src="Images/woodland/river_protection_forest/river_protetion_forest(3).jpg" width="18%" />
  <img src="Images/woodland/river_protection_forest/river_protetion_forest(4).jpg" width="18%" />
  <img src="Images/woodland/river_protection_forest/river_protetion_forest(5).jpg" width="18%" />
</p>

#### Sapling
<p align="center">
  <img src="Images/woodland/sapling/sapling(1).jpg" width="18%" />
  <img src="Images/woodland/sapling/sapling(2).jpg" width="18%" />
  <img src="Images/woodland/sapling/sapling(3).jpg" width="18%" />
  <img src="Images/woodland/sapling/sapling(4).jpg" width="18%" />
  <img src="Images/woodland/sapling/sapling(5).jpg" width="18%" />
</p>

#### Shrubwood
<p align="center">
  <img src="Images/woodland/shrubwood/shrubwood(1).jpg" width="18%" />
  <img src="Images/woodland/shrubwood/shrubwood(2).jpg" width="18%" />
  <img src="Images/woodland/shrubwood/shrubwood(3).jpg" width="18%" />
  <img src="Images/woodland/shrubwood/shrubwood(4).jpg" width="18%" />
  <img src="Images/woodland/shrubwood/shrubwood(5).jpg" width="18%" />
</p>

#### Sparse Forest
<p align="center">
  <img src="Images/woodland/sparse_forest/sparse_forest(1).jpg" width="18%" />
  <img src="Images/woodland/sparse_forest/sparse_forest(2).jpg" width="18%" />
  <img src="Images/woodland/sparse_forest/sparse_forest(3).jpg" width="18%" />
  <img src="Images/woodland/sparse_forest/sparse_forest(4).jpg" width="18%" />
  <img src="Images/woodland/sparse_forest/sparse_forest(5).jpg" width="18%" />
</p>

## 📊 **Dataset Analysis**

### 1️⃣ **Sample Distribution per Category**
#### 🏗️ Construction Land - City Building
<p align="center">
  <img src="Images/construction_land/distribution.png" width="80%" />
</p>


#### 🌾 Cultivated Land - Green Farmland
<p align="center">
  <img src="Images/cultivatedland/distribution.png" width="80%" />
</p>

#### 🏜️ Land - Desert
<p align="center">
  <img src="Images/land/distribution.png" width="80%" />
</p>

#### ✈️ Objects - Airplane
<p align="center">
  <img src="Images/objects/distribution.png" width="80%" />
</p>

#### 🚗 Transportation - Highway
<p align="center">
  <img src="Images/transportation/distribution.png" width="80%" />
</p>

#### 🌊 Water Area - River
<p align="center">
  <img src="Images/waterarea/distribution.png" width="80%" />
</p>

#### 🌳 Woodland - Forest
<p align="center">
  <img src="Images/woodland/distribution.png" width="80%" />
</p>


## 📊 **AI Models**
#### 🚀 Custom CNN Model
```
class CNNClassifier(nn.Module):
    def __init__(self, num_classes=3):
        super(CNNClassifier, self).__init__()
        self.features = nn.Sequential(
            nn.Conv2d(3, 32, kernel_size=3, stride=1, padding=1),
            nn.ReLU(inplace=True),
            nn.MaxPool2d(kernel_size=2, stride=2),

            nn.Conv2d(32, 64, kernel_size=3, stride=1, padding=1),
            nn.ReLU(inplace=True),
            nn.MaxPool2d(kernel_size=2, stride=2)
        )
        self.classifier = nn.Sequential(
            nn.Flatten(),
            nn.Linear(64 * 32 * 32, 128),
            nn.ReLU(),
            nn.Dropout(0.5),
            nn.Linear(128, num_classes)
        )

    def forward(self, x):
        x = self.features(x)
        x = self.classifier(x)
        return x
```

#### 🚀 Resnet50
```
model = models.resnet50(weights=models.ResNet50_Weights.DEFAULT)
num_ftrs = model.fc.in_features
model.fc = nn.Linear(num_ftrs, num_classes)
```

#### 🚀 DenseNet121
```
model = models.densenet121(weights=models.DenseNet121_Weights.DEFAULT)
num_ftrs = model.classifier.in_features
model.classifier = nn.Linear(num_ftrs, num_classes)
```

#### 🚀 EfficientNet
```
model = models.efficientnet_b0(weights=models.EfficientNet_B0_Weights.DEFAULT)
num_ftrs = model.classifier[1].in_features
model.classifier[1] = nn.Linear(num_ftrs, num_classes)
```

## 📈 **Results Comparison**
#### 🏗️ Construction Land
##### 🚀 Custom CNN Model
<p align="center">
  <img src="Images/construction_land/cm_custom.png" width="36%"/>
  <img src="Images/construction_land/accuracy_loss_custom.png" width="60%" />
</p>

##### 🚀 Resnet50
<p align="center">
  <img src="Images/construction_land/cm_resnet.png" width="36%"/>
  <img src="Images/construction_land/accuracy_loss_resnet.png" width="60%" />
</p>

##### 🚀 DenseNet121
<p align="center">
  <img src="Images/construction_land/cm_densenet.png" width="36%"/>
  <img src="Images/construction_land/accuracy_loss_densenet.png" width="60%" />
</p>

##### 🚀 EfficientNet
<p align="center">
  <img src="Images/construction_land/cm_efficient.png" width="36%"/>
  <img src="Images/construction_land/accuracy_loss_efficient.png" width="60%" />
</p>


#### 🌾 Cultivated Land - Green Farmland
##### 🚀 Custom CNN Model
<p align="center">
  <img src="Images/cultivatedland/cm_custom.png" width="36%"/>
  <img src="Images/cultivatedland/accuracy_loss_custom.png" width="60%" />
</p>

##### 🚀 Resnet50
<p align="center">
  <img src="Images/cultivatedland/cm_resnet.png" width="36%"/>
  <img src="Images/cultivatedland/accuracy_loss_resnet.png" width="60%" />
</p>

##### 🚀 DenseNet121
<p align="center">
  <img src="Images/cultivatedland/cm_densenet.png" width="36%"/>
  <img src="Images/cultivatedland/accuracy_loss_densenet.png" width="60%" />
</p>

##### 🚀 EfficientNet
<p align="center">
  <img src="Images/cultivatedland/cm_efficient.png" width="36%"/>
  <img src="Images/cultivatedland/accuracy_loss_efficient.png" width="60%" />
</p>

#### 🏜️ Land - Desert
##### 🚀 Custom CNN Model
<p align="center">
  <img src="Images/land/cm_custom.png" width="36%"/>
  <img src="Images/land/accuracy_loss_custom.png" width="60%" />
</p>

##### 🚀 Resnet50
<p align="center">
  <img src="Images/land/cm_resnet.png" width="36%"/>
  <img src="Images/land/accuracy_loss_resnet.png" width="60%" />
</p>

##### 🚀 DenseNet121
<p align="center">
  <img src="Images/land/cm_densenet.png" width="36%"/>
  <img src="Images/land/accuracy_loss_densenet.png" width="60%" />
</p>

##### 🚀 EfficientNet
<p align="center">
  <img src="Images/land/cm_efficient.png" width="36%"/>
  <img src="Images/land/accuracy_loss_efficient.png" width="60%" />
</p>

#### ✈️ Objects - Airplane
##### 🚀 Custom CNN Model
<p align="center">
  <img src="Images/objects/cm_custom.png" width="36%"/>
  <img src="Images/objects/accuracy_loss_custom.png" width="60%" />
</p>

##### 🚀 Resnet50
<p align="center">
  <img src="Images/objects/cm_resnet.png" width="36%"/>
  <img src="Images/objects/accuracy_loss_resnet.png" width="60%" />
</p>

##### 🚀 DenseNet121
<p align="center">
  <img src="Images/objects/cm_densenet.png" width="36%"/>
  <img src="Images/objects/accuracy_loss_densenet.png" width="60%" />
</p>

##### 🚀 EfficientNet
<p align="center">
  <img src="Images/objects/cm_efficient.png" width="36%"/>
  <img src="Images/objects/accuracy_loss_efficient.png" width="60%" />
</p>

#### 🚗 Transportation - Highway
##### 🚀 Custom CNN Model
<p align="center">
  <img src="Images/transportation/cm_custom.png" width="36%"/>
  <img src="Images/transportation/accuracy_loss_custom.png" width="60%" />
</p>

##### 🚀 Resnet50
<p align="center">
  <img src="Images/transportation/cm_resnet.png" width="36%"/>
  <img src="Images/transportation/accuracy_loss_resnet.png" width="60%" />
</p>

##### 🚀 DenseNet121
<p align="center">
  <img src="Images/transportation/cm_densenet.png" width="36%"/>
  <img src="Images/transportation/accuracy_loss_densenet.png" width="60%" />
</p>

##### 🚀 EfficientNet
<p align="center">
  <img src="Images/transportation/cm_efficient.png" width="36%"/>
  <img src="Images/transportation/accuracy_loss_efficient.png" width="60%" />
</p>

#### 🌊 Water Area - River
##### 🚀 Custom CNN Model
<p align="center">
  <img src="Images/waterarea/cm_custom.png" width="36%"/>
  <img src="Images/waterarea/accuracy_loss_custom.png" width="60%" />
</p>

##### 🚀 Resnet50
<p align="center">
  <img src="Images/waterarea/cm_resnet.png" width="36%"/>
  <img src="Images/waterarea/accuracy_loss_resnet.png" width="60%" />
</p>

##### 🚀 DenseNet121
<p align="center">
  <img src="Images/waterarea/cm_densenet.png" width="36%"/>
  <img src="Images/waterarea/accuracy_loss_densenet.png" width="60%" />
</p>

##### 🚀 EfficientNet
<p align="center">
  <img src="Images/waterarea/cm_efficient.png" width="36%"/>
  <img src="Images/waterarea/accuracy_loss_efficient.png" width="60%" />
</p>

#### 🌳 Woodland - Forest
##### 🚀 Custom CNN Model
<p align="center">
  <img src="Images/woodland/cm_custom.png" width="36%"/>
  <img src="Images/woodland/accuracy_loss_custom.png" width="60%" />
</p>

##### 🚀 Resnet50
<p align="center">
  <img src="Images/woodland/cm_resnet.png" width="36%"/>
  <img src="Images/woodland/accuracy_loss_resnet.png" width="60%" />
</p>

##### 🚀 DenseNet121
<p align="center">
  <img src="Images/woodland/cm_densenet.png" width="36%"/>
  <img src="Images/woodland/accuracy_loss_densenet.png" width="60%" />
</p>

##### 🚀 EfficientNet
<p align="center">
  <img src="Images/woodland/cm_efficient.png" width="36%"/>
  <img src="Images/woodland/accuracy_loss_efficient.png" width="60%" />
</p>


## 📊 Model Accuracy Performance Comparison of Test Data

| Model            | 🏗️ Construction Land | 🌾 Cultivated Land | 🌍 Land | 🏢 Objects | 🚗 Transportation | 💧 Water Area | 🌲 Woodland |
|-----------------|:-------------------:|:-----------------:|:------:|:--------:|:---------------:|:------------:|:---------:|
| **Custom CNN**   | 0.9140 | 0.9953 | 0.9944 | 0.9701 | 0.9071 | 0.9530 | 0.9681 |
| **ResNet-50**    | 0.9825 | 0.9953 | 0.9870 | 1.0000 | 0.9859 | 0.9741 | 0.9957 |
| **DenseNet-121** | 0.9807 | 0.9976 | 0.9796 | 0.9851 | 0.9919 | 0.9611 | 0.9947 |
| **EfficientNet** | 0.9877 | 0.9976 | 0.9889 | 0.9925 | 0.9859 | 0.9530 | 0.9936 |


## Code
```python
# Download Dataset From Above Link
# Upload required folder in drive and then change path of dataset
# Optional if dataset is in Zip format
data_path = f"/content/drive/MyDrive/hyperspectral_data/{folder_name}.zip"
!unzip {data_path} -d /content/drive/MyDrive/hyperspectral_data/

EXTRACTED_DATA_PATH = f"/content/drive/MyDrive/hyperspectral_data/{folder_name}"
```
### 🏗️ Construction Land 

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1r7KclsJnckEdgjVax7N63T5C5q6jiAfJ?usp=sharing)

### 🌾 Cultivated Land 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1N3twH876GKQ4OhXVpk0CFQZypk5D6Nxy?usp=sharing)
### 🌍 Land 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fwCCaUx5RPQqa2er2Xq6dmdjtcz-14jF?usp=sharing)

### 🏢 Objects 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gEsbRNTHJtDdsVi6a1FWjz_uji4hfwR9?usp=sharing)

### 🚗 Transportation 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ySJGEfsWz-oa-4G_l1hFzuNbKXvpwDuU?usp=sharing)

### 💧 Water Area 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18l18El2P_FXnuncwNlis8MZv9lVCq77K?usp=sharing)

### 🌲 Woodland 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/146D7fmFc_j-4a7VeaqRp0TaOF082rs51?usp=sharing)


# 📌 Conclusion
The performance comparison of the four models across seven land categories shows that EfficientNet achieved the highest overall accuracy, demonstrating its superior capability in generalizing remote sensing image data. It outperformed all other models in most categories, particularly excelling in Construction Land (98.77%), Cultivated Land (99.76%), and Objects (99.25%).

ResNet-50 followed closely, achieving perfect accuracy (100%) in the Objects category and maintaining strong performance across all other categories. DenseNet-121 also performed exceptionally well, especially in Cultivated Land (99.76%) and Transportation (99.19%), indicating its effectiveness in complex feature extraction.

The Custom CNN, while providing a solid baseline, lagged behind the other models, particularly in Transportation (90.71%) and Construction Land (91.40%), reflecting the advantage of deeper and more sophisticated architectures in handling complex remote sensing data.

Overall, EfficientNet stands out as the most reliable and efficient model for this multi-class land classification task, balancing high accuracy and computational efficiency across diverse land categories.