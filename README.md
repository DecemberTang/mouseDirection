# mouseDirection
when a mouse enter into a box, we can find out its entering direction.
当鼠标进入一个div后，记录鼠标的坐标，div的中心及四个角的坐标，用坐标分别算出div两对角线斜率k1，k2,和鼠标位置的斜率k，如果k1<k<k2时，鼠标进入方向为right或者为left，如果位置坐标的横坐标大于中心横坐标，则为right，反之为left。其余情况鼠标的进入方向为
top或者bottom，如果位置的纵坐标大于中心的纵坐标，则为bottom，反之为top
