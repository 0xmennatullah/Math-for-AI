## solving linear eq system

### non-singular
- determinant != 0 
- ![eq process](./img/image.png)

### singular
- determinant = 0
#### redundant systems: 

- anthing u do to the equation 1 affects the equation 2 as they're drived from weach other, so any manipulation will not lead to any change, will always give us 0 = 0 
  
#### contradictory systems: 
- each equation contradicts the others, so we got similar vars yet different results from em, so when we apply mathematical trans upon them we get contradiction nums, like 0 = 2

### solving +2 vars systems of equations:
- elimination method:
  - ![eliminate](./img/image-1.png)


### matrix row reduction
- basically representing elimination but in matrices
  - ![mat reduction](./img/image-2.png)

#### row echelon form
``` zero rows are at the bottom, and the leading entry (the first non-zero number) in each non-zero row is to the right of the leading entry in the row above it``` 

##### preserving singularity
  - ![gen form](./img/image-3.png)
  - it preserves singularity, doesn't affect it, just changes the determinent's sign or so.
  - we could change order of rows => -det
  - mult by scalar(non-zero) => det*scalar
  - add rows => det

##### echelon & rank
1. compressing image: reducing rank
   1. rank depend on num of info the system holds
   2. ![ranks](./img/image-4.png)
   3. ![rank vs sol](./img/image-5.png)
   4. ![rank vs sing](./img/image-6.png)
   5. ![all ranks](./img/image-7.png)
   6. ![singul](./img/image-8.png)
   7. ![+2 vars](./img/image-9.png)
   8. ![pivot](./img/image-10.png)
   9. ![row form](./img/image-11.png)
   10. rank of matrices: diagonal ones, most left after the prev ![1s row ech](./img/image-12.png)
   

### gaussian elimination algorithm
- augmented matrix => use ti solve our sys of equations => elimination method
- set pivotes to one, rest to zeros
- ![singulars](./img/image-13.png)
  - butttt, we don't know if it's no solutions or infinity
  - ![inf](./img/image-14.png)
  - ![no sol](./img/image-15.png)
  - ![conc](./img/image-16.png)
  


  







