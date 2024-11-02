points=[(8, 5),
 (-7, 3),
 (9, 3),
 (-10, -3),
 (-3, 3),
 (-1, -10),
 (-6, 3),
 (8, 10),
 (-10, 2),
 (1, 5)]
distances=[]

def euclideanDistance(nokta1,nokta2):
    x2,y2=nokta2
    x1,y1=nokta1
    return (((x2-x1)**2)+((y2-y1)**2))**(1/2)
    
for i in range(len(points)-1):
    mesafe=euclideanDistance(points[i],points[i+1])
    distances.append(mesafe)

min=distances[0]

for i in range(len(distances)):
    if(distances[i]<min):
        min=distances[i]
print(min)
