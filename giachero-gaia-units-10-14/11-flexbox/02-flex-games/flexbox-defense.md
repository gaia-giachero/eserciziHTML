# **FLEXBOX DEFENSE**
### ESERCIZIO 1
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: center;
}
```
---
### ESERCIZIO 2
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: flex-end;
}
.tower-group-2 {
    display: flex;
    justify-content: space-around;
}
.tower-group-3 {
    display: flex;
    justify-content: flex-end;
}
```
---
### ESERCIZIO 3
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: center;
}
.tower-group-2 {
    display: flex;
    justify-content: space-between;
}
```
---
### ESERCIZIO 4
``` CSS
.tower-group-1 {
    display: flex;
    align-items: flex-end;
}
.tower-group-2 {
    display: flex;
    align-items: flex-end;
}
```
---
### ESERCIZIO 5
``` CSS
.tower-group-1 {
    display: flex;
    align-items: flex-end;
    justify-content: space-around;
}
.tower-group-2 {
    display: flex;
    justify-content: center;
}
.tower-group-3 {
    display: flex;
    align-items: center;
    justify-content: space-around;
}
```
---
### ESERCIZIO 6
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```
---
### ESERCIZIO 7
``` CSS
.tower-group-1 {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.tower-group-2 {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
```
---
### ESERCIZIO 8
``` CSS
.tower-group-1 {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.tower-group-2 {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}
```
---
### ESERCIZIO 9
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: space-around;
    flex-direction: row-reverse;
    align-items: center;
}
.tower-group-2 {
    display: flex;
    justify-content: space-around;
    flex-direction: row-reverse;
    align-items: center;
}
```
---
### ESERCIZIO 10
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: space-around;
}
.tower-1-2 {
    order: 1;
}
.tower-group-2 {
    display: flex;
    justify-content: space-around;
}
.tower-2-2 {
    order: -1;
}
```
---
### ESERCIZIO 11
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: space-between;
}
.tower-1-1 {
    align-self: flex-end;
}
.tower-1-2 {
    align-self: flex-start;
}
.tower-1-3 {
    align-self: flex-end;
}
.tower-1-4 {
    align-self: flex-start;
}
```
---
### ESERCIZIO 12
``` CSS
.tower-group-1 {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.tower-1-1 {
    order: -1;
    align-self: flex-start;
}
.tower-1-2 {
    order: 0;
}
.tower-1-3 {
    order: 2;
}
.tower-1-4 {
    order: 1;
}
.tower-1-5 {
    order: 5;
    align-self: flex-end;
}
```