# 9.自定义msg
ROS 中通过 std_msgs 封装了一些原生的数据类型,比如:String、Int32、Int64、Char、Bool、Empty.... 但是，这些数据一般只包含一个 data 字段，结构的单一意味着功能上的局限性，当传输一些复杂的数据，比如: 激光雷达的信息... std_msgs 由于描述性较差而显得力不从心，这种场景下可以使用自定义的消息类型  
msgs只是简单的文本文件，每行具有字段类型和字段名称，可以使用的字段类型有：  
    int8, int16, int32, int64 (或者无符号类型: uint*)

    float32, float64

    string

    time, duration

    other msg files

    variable-length array[] and fixed-length array[C]
>ROS中还有一种特殊类型：Header，标头包含时间戳和ROS中常用的坐标帧信息。会经常看到msg文件的第一行具有Header标头。