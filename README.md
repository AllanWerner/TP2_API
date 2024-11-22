# TP2_API
Requête API publique 

1 - Requête GET pour les comments 
https://jsonplaceholder.typicode.com/comments

2 - Requête POST sur les todos pour créer un objet 
https://jsonplaceholder.typicode.com/todos
{
    "userId": 7,
    "title": "Objet appartenant à Allan Werner",
    "completed": true
}

3 - Requête PATCH sur les posts 
https://jsonplaceholder.typicode.com/posts/100
{
    "title": "Post modifié par Allan Werner",
    "body": "Le post a été modifié avec succès !"
}

4 - Requête GET pour afficher les commentaires liés au post ayant l'id 1
https://jsonplaceholder.typicode.com/comments?postId=1

5 - Requête GET permettant d'afficher les photos affiliés à l'album 2
https://jsonplaceholder.typicode.com/photos?albumId=2
