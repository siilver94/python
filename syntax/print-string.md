## **문자열 출력**

<br/>
<br/>

**빈 자리는 빈 공간으로 두고, 오른쪽으로 정렬 , 총 10자리 공간 확보**

```python
print("{0:>10}".format(500))
```

`500`

<br/>

**양수일땐 +, 음수일땐 - 로 표시**

```python
print("{0:>+10}".format(500))
print("{0:>+10}".format(-500))
```

`+500`

`500`

<br/>

**왼쪽 정렬 , 빈칸을 '_'로 채움, 부호**

```python
print("{0:_<+10}".format(500))
```

`+500______`

<br/>

**3자리 마다 콤마 찍기, 음수 양수 구별**

```python
print("{0:+,}".format(10000000000))
```

`+10,000,000,000`

<br/>

**3자리 마다 콤마, 부호, 자릿수 확보 빈 자리는 '^'**

```python
print("{0:^<+30,}".format(10000000000))
```

`+10,000,000,000^^^^^^^^^^^^^^^`

<br/>

**소수점 2번쨰 자리까지 출력**

```python
print("{0:.2f}".format(5/3))
```

`1.67`