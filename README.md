问题：
代码仅仅在ether和IP层之间加了一个layer（类似于basic_tunnel）
观察了pcap文件 standard_metadata.timedelta会随着h2发送干扰包增大 但是增大的幅度很小（正常情况下是从10+到100000+）
standard_metadata.qlength始终为0  
感觉是没有造成拥塞。
