11111---for first commit
22222---for second commit
33333---for third commit 
44444---for fourth commit on feature1 branch
55555---for fifth commit on feature2 branch
55555---此时master和feature2已经往前演进了一个commit，此时产生的提交会导致feature1和master diverge，先尝试merge试试看，预期会产生一个merge commit
fix conflict, 即将产生一个新的merge commit
master继续演进
