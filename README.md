# icp
Python implementation of m-dimensional Iterative Closest Point method.  ICP finds a best fit rigid body transformation between two point sets.  Correspondence between the points is not assumed. Included is an SVD-based least-squared best-fit algorithm for corresponding point sets.

```bash
python test.py
```
ClayFlannigan 

[참고 페이지](https://daddynkidsmakers.blogspot.com/2021/09/icpiterative-closest-point.html)

# icp_open3d
- [ICP registraion](http://www.open3d.org/docs/0.7.0/tutorial/Basic/icp_registration.html#point-to-point-icp)
- AttributeError: module 'open3d' has no attribute 'registration'
에러발생. 그리고 point cloud로 해야해서
