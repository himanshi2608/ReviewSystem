# ReviewSystem
Eg: Amazon or movie reviews
x=["this product is not good enough"]
h=tfidf_v.transform(x)
y=model.predict(h)
def find(y):
    if y == 1:
        print ("Review is positive")
    else:
        print ("Review is negative")

find(y)

# Output 
Review is negative