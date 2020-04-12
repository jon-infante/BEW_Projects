1. To filter all the books with titles containing the word 'Django' we would use Book.objects.filter(title__contains='Django')
2. To filter for all the books with tag 'Fiction' we would use Book.objects.filter(tags__contains='Fiction')
3. To filter for all the authors who have written books containing the word 'Django' we would use Book.objects.author.filter(title__contains='Django')
