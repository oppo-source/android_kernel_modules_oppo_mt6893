#
# Copyright (C) 2015 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#

# Zhao.Pan@MULTIMEDIA.AUDIODRIVER.MACHINE, 2020/10/10, add for audiohal feedback
obj-y += driver/
# Zhao.Pan@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2020/04/28, add for aw87339 PA
#obj-y += aw87339/
# Jingjing.Jiang@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2020/05/19, add for tfa98xx smartPA
obj-$(CONFIG_SND_SOC_TFA9874) += tfa98xx/
# Yongpei.Yao@MULTIMEDIA.AUDIODRIVER.HEADSET, 2021/02/23, add for fsa switch
obj-$(CONFIG_SND_SOC_FSA) += fsa44xx/
# Jianqing.Liao@MULTIMEDIA.AUDIODRIVER.TFA_HAPTIC, 2021/04/15, add for tfa haptic
obj-$(CONFIG_SND_SOC_TFA_HAPTIC) += tfa_haptic/
