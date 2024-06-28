---
title: "Spark Architecture"
date: 2022-06-04T16:37:11+05:30
#draft: true
tags: ["Spark","Python"]
categories: ["Spark"]

featuredImage: "/images/Spark Architecture.png"
featuredImageCaption: "Hadoop Architecture"
featuredImagePreview: "/images/Spark Architecture preview.png"

---




{{< admonition type=note title="Note" open=true >}}
This is dump blog, will soon start writing real ones.
{{< /admonition >}}

## Intro

In Python, we can implement a matrix as a nested list (list inside a list). We can treat each element as a row of the matrix.

For example X = [[1, 2], [4, 5], [3, 6]] would represent a 3x2 matrix. The first row can be selected as X[0]. And, the element in the first-row first column can be selected as X[0][0].

Transpose of a matrix is the interchanging of rows and columns. It is denoted as X'. The element at ith row and jth column in X will be placed at jth row and ith column in X'. So if X is a 3x2 matrix, X' will be a 2x3 matrix.

```python
print("hello World, here is a example to transpose a matrix using list comprehension")

X = [[12,7],
    [4 ,5],
    [3 ,8]]

result = [[X[j][i] for j in range(len(X))] for i in range(len(X[0]))]

for r in result:
   print(r)
```
## My heading

{{< echarts >}}
[title]
text = "Summary Line Chart"
top = "2%"
left = "center"

[tooltip]
trigger = "axis"

[legend]
data = [
  "Email Marketing",
  "Affiliate Advertising",
  "Video Advertising",
  "Direct View",
  "Search Engine"
]
top = "10%"

[grid]
left = "5%"
right = "5%"
bottom = "5%"
top = "20%"
containLabel = true

[toolbox]
[toolbox.feature]
[toolbox.feature.saveAsImage]
title = "Save as Image"

[xAxis]
type = "category"
boundaryGap = false
data = [
  "Monday",
  "Tuesday",
  "Wednesday",
  "Thursday",
  "Friday",
  "Saturday",
  "Sunday"
]

[yAxis]
type = "value"

[[series]]
name = "Email Marketing"
type = "line"
stack = "Total"
data = [
  120.0,
  132.0,
  101.0,
  134.0,
  90.0,
  230.0,
  210.0
]

[[series]]
name = "Affiliate Advertising"
type = "line"
stack = "Total"
data = [
  220.0,
  182.0,
  191.0,
  234.0,
  290.0,
  330.0,
  310.0
]

[[series]]
name = "Video Advertising"
type = "line"
stack = "Total"
data = [
  150.0,
  232.0,
  201.0,
  154.0,
  190.0,
  330.0,
  410.0
]

[[series]]
name = "Direct View"
type = "line"
stack = "Total"
data = [
  320.0,
  332.0,
  301.0,
  334.0,
  390.0,
  330.0,
  320.0
]

[[series]]
name = "Search Engine"
type = "line"
stack = "Total"
data = [
  820.0,
  932.0,
  901.0,
  934.0,
  1290.0,
  1330.0,
  1320.0
]
{{< /echarts >}}

### sub heading

{{< mermaid >}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

{{< typeit code=java >}}
public class HelloWorld {
    public static void main(String []args) {
        System.out.println("Hello World");
    }
}
{{< /typeit >}}



