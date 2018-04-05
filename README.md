# TarantulaPy

A minimalistic implementation of Tarantula Program Fault Localization Tool in Python

## Getting Started

python tarantula.py <Source_Code> <Test_Suite_File>

If you want to test tarantula on file mid.py

```
python tarantula.py mid.py testCaseMid
```

### Expected Output

```
Line	Suspiciousness	Rank	(3, 3, 5)	(1, 2, 3)	(3, 2, 1)	(5, 5, 5)	(5, 3, 4)	(2, 1, 3)
1	0.5		7				m = y
2	0.5		7			elif (x<z):
3	0.5		7			if(x<y):
4	0.625		3	def mid(x,y,z):
5	0.0		13		m = z
6	0.714		2		if (y<z):
7	0.833		1		return m
8	0.0		13				m = y
9	0.0		13		else:
10	0.0		13			if(x>y):
11	0.0		13				m = y
12	0.0		13			elif (x>z):
13	0.5		7				m = x
				True		True		True		True		True		False

```

## Built With

* [SpiderLab](http://spideruci.org/fault-localization/) - The team behind tarantula technique
* [Paper](http://spideruci.org/papers/jones05.pdf) - Research Paper on Evaluation and Algorithm itself

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Ali Ahsan** - *Initial work* - [Ali Ahsan](https://github.com/aliahsan07)
* **Zain Qasmi** - *Initial work* - [Zain Qasmi](https://github.com/ZainQasmi)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* **Junaid Haroon Siddiqui** - *Project Supervisor* - [Junaid Haroon Siddiqui](https://github.com/jsiddiqui)
