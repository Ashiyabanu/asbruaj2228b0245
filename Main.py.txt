def linearsearchproduct(ProductList, targetproduct):
  indices = []

  for index, product in enumerate(ProductList):
    if product == targetproduct:
      indices.append(index)

  return indices


Products = ["Shoes", "boot", "loafer", "shoes", "sandal", "shoes"]
target = "shoes"
target2 = 'apple'
result = linearsearchproduct(Products, target)
print(result)
