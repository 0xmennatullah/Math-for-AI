### principal component analysis

#### Singularity and rank of linear transformation
- ![rank of trans](./img/image.png)
- it depends on how the transformation affect the plane it applies upon
- if it results transformation for the whole plane => it's non-singular + rank 2 => resulting 2 dimensions
- if resulted change in a line => one dimension => ranks one
- if a point (0,0) => rank 0, 0 dimmensions

#### determinant as an area
- determinent of the transformation matrix = area of resulting shape
- ![area](./img/image-1.png)
-  negative area => depend on order only, doesn't really matter
  
- inverses:
  - non-singular => doesn't have inverse


### bases and eigen values
- bases can't be in the same direction

#### span
- the space that contains the vector 
- dependency ![dep](./img/image-2.png)
- ![summary](./img/image-3.png)
  
#### eigen bases
- eigen vector => AV = M*V1
- ![eigen vec](./img/image-4.png)
- eigen vector is scalar * basis vector
- ![summary](./img/image-5.png)
- eigening => stretching basis in some direction, no trans


### dimensionality reduction
- ![projection](./img/image-6.png)
- ![PCA](./img/image-7.png)
- decides how the spreadness of the dagtga helps us extract info from it, the more spreadded the better info extraction

#### some def
- ![mean](./img/image-8.png)
- ![var](./img/image-9.png)
- ![var2](./img/image-10.png)
- ![var3](./img/image-11.png)
- covarience: when we have identical varience, we wanna decide how data features varies in respect for one another 
- ![co-var](./img/image-12.png)
- 
