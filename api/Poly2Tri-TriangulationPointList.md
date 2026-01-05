# Class TriangulationPointList

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TriangulationPointList : Point2DList, IList<Point2D>, ICollection<Point2D>, IEnumerable<Point2D>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Point2DList](/api/Poly2Tri-Point2DList) → TriangulationPointList

## Inherited Members
[kMaxPolygonVertices](/api/Poly2Tri-Point2DList#kmaxpolygonvertices), [kLinearSlop](/api/Poly2Tri-Point2DList#klinearslop), [kAngularSlop](/api/Poly2Tri-Point2DList#kangularslop), [mPoints](/api/Poly2Tri-Point2DList#mpoints), [mBoundingBox](/api/Poly2Tri-Point2DList#mboundingbox), [mWindingOrder](/api/Poly2Tri-Point2DList#mwindingorder), [mEpsilon](/api/Poly2Tri-Point2DList#mepsilon), [ToString()](/api/Poly2Tri-Point2DList#tostring), [Clear()](/api/Poly2Tri-Point2DList#clear), [IndexOf(Point2D)](/api/Poly2Tri-Point2DList#indexof-point2d), [Add(Point2D)](/api/Poly2Tri-Point2DList#add-point2d), [Add(Point2D, int, bool)](/api/Poly2Tri-Point2DList#add-point2d-int-bool), [AddRange(Point2DList)](/api/Poly2Tri-Point2DList#addrange-point2dlist), [AddRange(IEnumerator<Point2D>, WindingOrderType)](/api/Poly2Tri-Point2DList#addrange-ienumerator-point2d-windingordertype), [Insert(int, Point2D)](/api/Poly2Tri-Point2DList#insert-int-point2d), [Remove(Point2D)](/api/Poly2Tri-Point2DList#remove-point2d), [RemoveAt(int)](/api/Poly2Tri-Point2DList#removeat-int), [RemoveRange(int, int)](/api/Poly2Tri-Point2DList#removerange-int-int), [Contains(Point2D)](/api/Poly2Tri-Point2DList#contains-point2d), [CopyTo(Point2D[], int)](/api/Poly2Tri-Point2DList#copyto-point2d-int), [CalculateBounds()](/api/Poly2Tri-Point2DList#calculatebounds), [CalculateEpsilon()](/api/Poly2Tri-Point2DList#calculateepsilon), [CalculateWindingOrder()](/api/Poly2Tri-Point2DList#calculatewindingorder), [NextIndex(int)](/api/Poly2Tri-Point2DList#nextindex-int), [PreviousIndex(int)](/api/Poly2Tri-Point2DList#previousindex-int), [GetSignedArea()](/api/Poly2Tri-Point2DList#getsignedarea), [GetArea()](/api/Poly2Tri-Point2DList#getarea), [GetCentroid()](/api/Poly2Tri-Point2DList#getcentroid), [Translate(Point2D)](/api/Poly2Tri-Point2DList#translate-point2d), [Scale(Point2D)](/api/Poly2Tri-Point2DList#scale-point2d), [Rotate(double)](/api/Poly2Tri-Point2DList#rotate-double), [IsDegenerate()](/api/Poly2Tri-Point2DList#isdegenerate), [IsConvex()](/api/Poly2Tri-Point2DList#isconvex), [IsSimple()](/api/Poly2Tri-Point2DList#issimple), [CheckPolygon()](/api/Poly2Tri-Point2DList#checkpolygon), [GetErrorString(PolygonError)](/api/Poly2Tri-Point2DList#geterrorstring-polygonerror), [RemoveDuplicateNeighborPoints()](/api/Poly2Tri-Point2DList#removeduplicateneighborpoints), [Simplify()](/api/Poly2Tri-Point2DList#simplify), [Simplify(double)](/api/Poly2Tri-Point2DList#simplify-double), [MergeParallelEdges(double)](/api/Poly2Tri-Point2DList#mergeparalleledges-double), [ProjectToAxis(Point2D, out double, out double)](/api/Poly2Tri-Point2DList#projecttoaxis-point2d-out-double-out-double), [BoundingBox](/api/Poly2Tri-Point2DList#boundingbox), [WindingOrder](/api/Poly2Tri-Point2DList#windingorder), [Epsilon](/api/Poly2Tri-Point2DList#epsilon), [this[int]](/api/Poly2Tri-Point2DList#this-int), [Count](/api/Poly2Tri-Point2DList#count), [IsReadOnly](/api/Poly2Tri-Point2DList#isreadonly), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TriangulationPointList()

```csharp
public TriangulationPointList()
```
