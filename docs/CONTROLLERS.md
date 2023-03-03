# Controllers

## PageController

### Routes publiques
 
- `/`
- `/a-propos`
- `/contact`
- `/demande-de-devis`


## ProjectCategoryController

### Routes publiques

- `/projets/:categorie`

### Routes privées

- `/admin/categories`
- `/admin/categories/ajouter`
- `/admin/categories/:id/details`
- `/admin/categories/:id/modifier`
- `/admin/categories/:id/supprimer`


## ProjectController

### Routes publiques

- `/projets`
- `/projets/:categorie/:projet`

### Routes privées

- `/admin/projets`
- `/admin/projets/ajouter`
- `/admin/projets/:id/details`
- `/admin/projets/:id/modifier`
- `/admin/projets/:id/supprimer`


## BlogController

### Routes publiques

- `/blog`
- `/blog/:article`


### Routes privées

- `/admin/blog`
- `/admin/blog/ajouter`
- `/admin/blog/:article/modifier`
- `/admin/blog/:article/details`
- `/admin/blog/:article/supprimer`


## MediaController

### Routes privées

- `/admin/medias`
- `/admin/medias/ajouter`
- `/admin/medias/:id/supprimer`