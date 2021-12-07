## sql批量插入问题
jdbc url加rewriteBatchedStatement=true 这样直接使用一个preparedStatement去执行 insert del update ；不然会拆成多个单个preaparedStatement去执行，所以性能会低
