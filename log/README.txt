(num of fault replica from 1 to 10)
./simpleTest.py -l DEBUG -i 5000 -nc -bft n=6,r=6,f=1,c=1,cl=2,testViewChange -p
./simpleTest.py -l DEBUG -i 5000 -nc -bft n=9,r=9,f=2,c=1,cl=2,testViewChange -p
./simpleTest.py -l DEBUG -i 5000 -nc -bft n=18,r=18,f=5,c=1,cl=2,testViewChange -p
./simpleTest.py -l DEBUG -i 5000 -nc -bft n=33,r=33,f=10,c=1,cl=2,testViewChange -p

(num of requests from 10000 to 50000)
./simpleTest.py -l DEBUG -i 10000 -nc -bft n=6,r=6,f=1,c=1,cl=2,testViewChange -p
./simpleTest.py -l DEBUG -i 10000 -nc -bft n=6,r=6,f=1,c=1,cl=3,testViewChange -p
./simpleTest.py -l DEBUG -i 10000 -nc -bft n=6,r=6,f=1,c=1,cl=4,testViewChange -p
./simpleTest.py -l DEBUG -i 10000 -nc -bft n=6,r=6,f=1,c=1,cl=5,testViewChange -p
