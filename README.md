# -
本小组负责杂物部分
from django.db import models
# 总物资
    # 总物资
class All_goods_and_materials(models.Model):
    # 桌子(个数)
    desk = models.IntegerField(default=0)
    # 办工作(大桌子)(个数)
    Office_table = models.IntegerField(default=0)
    # 凳子(个数)
    stool = models.IntegerField(default=0)
    # 多媒体(个数)
    multimedia = models.IntegerField(default=0)
    # 空调(个数)
    air_conditioner = models.IntegerField(default=0)
    # 灯泡(个数)
    lamp_bulb = models.IntegerField(default=0)
    # 灭火器(个数)
    fire_extinguisher = models.IntegerField(default=0)
    # 床单被褥(套)
    bed_sheet = models.IntegerField(default=0)
    # 床铺(个数)
    bed = models.IntegerField(default=0)
    # 柜子(个数)
    cabinet = models.IntegerField(default=0)
    # 西服(套)
    western_style_clothes = models.IntegerField(default=0)
# 仓库
    # 仓库
class Warehouse(models.Model):
    # 桌子(个数)
    desk = models.IntegerField(default=0)
    # 办工作(大桌子)(个数)
    Office_table = models.IntegerField(default=0)
    # 凳子(个数)
    stool = models.IntegerField(default=0)
    # 多媒体(个数)
    multimedia = models.IntegerField(default=0)
    # 空调(个数)
    air_conditioner = models.IntegerField(default=0)
    # 灯泡(个数)
    lamp_bulb = models.IntegerField(default=0)
    # 灭火器(个数)
    fire_extinguisher = models.IntegerField(default=0)
    # 床单被褥(套)
    bed_sheet = models.IntegerField(default=0)
    # 床铺(个数)
    bed = models.IntegerField(default=0)
    # 柜子(个数)
    cabinet = models.IntegerField(default=0)
    # 西服(套)
    western_style_clothes = models.IntegerField(default=0)
# 教室
    # 教室
class Classroom(models.Model):
    # 班级(班号)
    class_no = models.CharField(max_length=20)
    # 桌子(个数)
    desk = models.IntegerField(default=0)
    # 办工作(大桌子)(个数)
    Office_table = models.IntegerField(default=0)
    # 凳子(个数)
    stool = models.IntegerField(default=0)
    # 多媒体(个数)
    multimedia = models.IntegerField(default=0)
    # 空调(个数)
    air_conditioner = models.IntegerField(default=0)
    # 灯泡(个数)
    lamp_bulb = models.IntegerField(default=0)
# 办公室
    # 办公室
class Office(models.Model):
    # 办公室名称
    office_name = models.CharField(max_length=20)
    # 桌子(个数)
    desk = models.IntegerField(default=0)
    # 办工作(大桌子)(个数)
    Office_table = models.IntegerField(default=0)
    # 凳子(个数)
    stool = models.IntegerField(default=0)
    # 多媒体(个数)
    multimedia = models.IntegerField(default=0)
    # 空调(个数)
    air_conditioner = models.IntegerField(default=0)
    # 灯泡(个数)
    lamp_bulb = models.IntegerField(default=0)
# 楼道
    # 楼道
class Corridor(models.Model):
    # 那个楼道
    corridor_name = models.CharField(max_length=20)
    # 灯泡(个数)
    lamp_bulb = models.IntegerField(default=0)
    # 灭火器(个数)
    fire_extinguisher = models.IntegerField(default=0)
# 宿舍
    # 宿舍
class Dorm(models.Model):
    # 床铺(个数)
    bed = models.IntegerField(default=0)
    # 柜子(个数)
    cabinet = models.IntegerField(default=0)
