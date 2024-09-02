**ant:- “ant” will build at file level**
(example: if we change any file(controller,dao) only that files will be build

**ant all**: “ant all” will build at extenstion level
(example :if we change any file in specific extension then that whole extension will build
ant all, while build it will not take care of folder structure of hybris.

**ant clean all**: “ant clean all” will delete all model classes and again it will be create.
ant clean all, while build it look for folder structure if folder structure is not proper it will recreate the folder structure of hybris.