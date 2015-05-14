# HBase-Import-From-File
input is file and split with one charecter it is user defined

java -jar hbase-example-0.0.1-SNAPSHOT.jar put
                                -f <file path>
                                -S <split character>
                                -c <column name>
                                -q <column qualifier>
                                -t <table>
                                
EXAMPLE
  
java -jar hbase-example-0.0.1-SNAPSHOT.jar put
                                          -f /home/input.txt
                                          -S ,
                                          -c rectangle
                                          -q minx,miny,maxx,maxy
                                          -t shape
