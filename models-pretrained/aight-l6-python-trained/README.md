---
tags:
- setfit
- sentence-transformers
- text-classification
- generated_from_setfit_trainer
widget:
- text: sep suppress | SkipTo
- text: the change permission limits a user s ability to view the change | Permission
- text: requires migrations checks | BaseCommand
- text: at groups 2, the operation becomes equivalent to having two conv | Conv3d
- text: categories index like, optional | CategoricalIndex
metrics:
- accuracy
pipeline_tag: text-classification
library_name: setfit
inference: false
datasets:
- NLBSE/nlbse25-code-comment-classification
---

# SetFit

This is a [SetFit](https://github.com/huggingface/setfit) model trained on the [NLBSE/nlbse25-code-comment-classification](https://huggingface.co/datasets/NLBSE/nlbse25-code-comment-classification) dataset that can be used for Text Classification. A MultiOutputClassifier instance is used for classification.

The model has been trained using an efficient few-shot learning technique that involves:

1. Fine-tuning a [Sentence Transformer](https://www.sbert.net) with contrastive learning.
2. Training a classification head with features from the fine-tuned Sentence Transformer.

## Model Details

### Model Description
- **Model Type:** SetFit
<!-- - **Sentence Transformer:** [Unknown](https://huggingface.co/unknown) -->
- **Classification head:** a MultiOutputClassifier instance
- **Maximum Sequence Length:** 256 tokens
- **Number of Classes:** 1884 classes
- **Training Dataset:** [NLBSE/nlbse25-code-comment-classification](https://huggingface.co/datasets/NLBSE/nlbse25-code-comment-classification)
<!-- - **Language:** Unknown -->
<!-- - **License:** Unknown -->

### Model Sources

- **Repository:** [SetFit on GitHub](https://github.com/huggingface/setfit)
- **Paper:** [Efficient Few-Shot Learning Without Prompts](https://arxiv.org/abs/2209.11055)
- **Blogpost:** [SetFit: Efficient Few-Shot Learning Without Prompts](https://huggingface.co/blog/setfit)

### Model Labels
| Label                   | Examples                                                                                                                                    |
|:------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------|
| tensor([0, 0, 0, 0, 1]) | <ul><li>'functionality. | AccessMixin'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'when it s used as a decorator, call wraps the execution of the | Atomic'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'when it s used as a context manager, enter creates a transaction or a | Atomic'</li></ul>                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'exit commits the transaction or releases the savepoint on normal exit, | Atomic'</li></ul>                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'it s possible to disable the creation of savepoints if the goal is to | Atomic'</li></ul>                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'a stack of savepoints identifiers is maintained as an attribute of the | Atomic'</li></ul>                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'none denotes the absence of a savepoint. | Atomic'</li></ul>                                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'implementation , there are only a few basic tests with the decorator | AtomicTests'</li></ul>                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'it is intended that autofieldmixin become public api when it is possible to | AutoFieldMeta'</li></ul>                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'stored in the database. | AutoFieldMeta'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'automatically generated field as a subclass of autofield. | AutoFieldMeta'</li></ul>                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'to be implemented on field to be used instead. | AutoFieldMeta'</li></ul>                                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'when these issues have been addressed, this metaclass could be used to | AutoFieldMeta'</li></ul>                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'for detecting automatically generated fields. | AutoFieldMeta'</li></ul>                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a service specific account of type bar. | BarAccount'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the base class from which all management commands ultimately | BaseCommand'</li></ul>                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'derive. | BaseCommand'</li></ul>                                                                                                   |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'use this class if you want access to all of the mechanisms which | BaseCommand'</li></ul>                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'parse the command line arguments and work out what code to call in | BaseCommand'</li></ul>                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'response if you don t need to change any of that behavior, | BaseCommand'</li></ul>                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'consider using one of the subclasses defined in this file. | BaseCommand'</li></ul>                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the command parsing and execution behavior, the normal flow works | BaseCommand'</li></ul>                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'django admin or manage^py loads the command class | BaseCommand'</li></ul>                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'and calls its run from argv method. | BaseCommand'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the run from argv method calls create parser to get | BaseCommand'</li></ul>                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'an argumentparser for the arguments, parses them, performs | BaseCommand'</li></ul>                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'any environment changes requested by options like | BaseCommand'</li></ul>                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pythonpath , and then calls the execute method, | BaseCommand'</li></ul>                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'passing the parsed arguments. | BaseCommand'</li></ul>                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'3 | BaseCommand'</li></ul>                                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the execute method attempts to carry out the command by | BaseCommand'</li></ul>                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'calling the handle method with the parsed arguments any | BaseCommand'</li></ul>                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output produced by handle will be printed to standard | BaseCommand'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output and, if the command is intended to produce a block of | BaseCommand'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sql statements, will be wrapped in begin and commit . | BaseCommand'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'4 | BaseCommand'</li></ul>                                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'if handle or execute raised any exception eg | BaseCommand'</li></ul>                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'commanderror , run from argv will instead print an error | BaseCommand'</li></ul>                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'message to stderr . | BaseCommand'</li></ul>                                                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'thus, the handle method is typically the starting point for | BaseCommand'</li></ul>                                               |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'subclasses many built in commands and command types either place | BaseCommand'</li></ul>                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'all of their logic in handle , or perform some additional | BaseCommand'</li></ul>                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'parsing work in handle and then delegate from it to more | BaseCommand'</li></ul>                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'specialized methods as needed. | BaseCommand'</li></ul>                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'several attributes affect behavior at various steps along the way | BaseCommand'</li></ul>                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'help | BaseCommand'</li></ul>                                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a short description of the command, which will be printed in | BaseCommand'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'output transaction | BaseCommand'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a boolean indicating whether the command outputs sql | BaseCommand'</li></ul>                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'statements if true , the output will automatically be | BaseCommand'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'wrapped with begin and commit . | BaseCommand'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'requires migrations checks | BaseCommand'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'migrations on disk don t match the migrations in the database. | BaseCommand'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a boolean if true , entire django project will be checked for errors | BaseCommand'</li></ul>                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'prior to executing the command. | BaseCommand'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'to validate an individual application s models | BaseCommand'</li></ul>                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'self^check app configs from handle , where app configs | BaseCommand'</li></ul>                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'app registry. | BaseCommand'</li></ul>                                                                                             |
| tensor([0, 0, 1, 0, 1]) | <ul><li>'this class and its subclasses are responsible for emitting schema changing | BaseDatabaseSchemaEditor'</li></ul>                   |
| tensor([0, 0, 1, 0, 1]) | <ul><li>'statements to the databases model creation removal alteration, field | BaseDatabaseSchemaEditor'</li></ul>                         |
| tensor([0, 0, 1, 0, 1]) | <ul><li>'renaming, index fiddling, and so on. | BaseDatabaseSchemaEditor'</li></ul>                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base class for all query expressions. | BaseExpression'</li></ul>                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base view for updating an existing object. | BaseUpdateView'</li></ul>                                                             |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'using this base class requires subclassing to provide a response mixin. | BaseUpdateView'</li></ul>                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'list of objects published in a given year. | BaseYearArchiveView'</li></ul>                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'secure password hashing using the bcrypt algorithm recommended | BCryptSHA256PasswordHasher'</li></ul>                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'this is considered by many to be the most secure algorithm but you | BCryptSHA256PasswordHasher'</li></ul>                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'must first install the bcrypt library. | BCryptSHA256PasswordHasher'</li></ul>                                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a container class used for iterating over widgets. | BoundWidget'</li></ul>                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this is useful for | BoundWidget'</li></ul>                                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'widgets that have choices. | BoundWidget'</li></ul>                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for example, the following can be used in a | BoundWidget'</li></ul>                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'template | BoundWidget'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'% for radio in myform^beatles % | BoundWidget'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'label for radio^id for label | BoundWidget'</li></ul>                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'radio^choice label | BoundWidget'</li></ul>                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'span class radio radio^tag span | BoundWidget'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'label | BoundWidget'</li></ul>                                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'% endfor % | BoundWidget'</li></ul>                                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a cache handler to manage access to cache instances. | CacheHandler'</li></ul>                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'ensure only one instance of each alias exists per thread. | CacheHandler'</li></ul>                                                |
| tensor([0, 1, 0, 0, 1]) | <ul><li>'class for creating enumerated choices. | Choices'</li></ul>                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an iterable that will yield chunks of data. | ChunkIter'</li></ul>                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'given a file like object as the | ChunkIter'</li></ul>                                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a class that can act as a client for testing purposes. | Client'</li></ul>                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'it allows the user to compose get and post requests, and | Client'</li></ul>                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the server response objects are annotated with the details | Client'</li></ul>                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'process of serving the request. | Client'</li></ul>                                                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'thus session details for the lifetime of the client instance. | Client'</li></ul>                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this is not intended as a replacement for twill selenium or | Client'</li></ul>                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'contexts and templates produced by a view, rather than the | Client'</li></ul>                                                     |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'html rendered to the end user. | Client'</li></ul>                                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'provide the ability to combine one or two objects with | Combinable'</li></ul>                                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'some connector. | Combinable'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for example f foo f bar . | Combinable'</li></ul>                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the second tab shows a windows command line equivalent of the usual | ConsoleDirective'</li></ul>                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests various hooks for using custom templates and contexts. | CustomArticleAdmin'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests for the ability to mixin a custom validate key method to | CustomCacheKeyValidationTests'</li></ul>                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'backend, and override the default key validation. | CustomCacheKeyValidationTests'</li></ul>                                       |
| tensor([0, 1, 0, 0, 1]) | <ul><li>'tests a custom remoteusermiddleware subclass with custom http auth user | CustomHeaderRemoteUserTest'</li></ul>                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'used in the tests for the database argument in signals #13552 | DatabaseReceiver'</li></ul>                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'in by reference as the last argument. | DblFromGeom'</li></ul>                                                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'invalid to field was passed to admin view via url query string | DisallowedModelAdminToField'</li></ul>                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'django specific rest to html tweaks. | DjangoHTMLTranslator'</li></ul>                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests for the earliest and latest objects methods | EarliestOrLatestTests'</li></ul>                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a collection of errors that knows how to display itself in various formats. | ErrorDict'</li></ul>                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'after pickling, this class fails unpickling with an error about incorrect | ExceptionThatFailsUnpickling'</li></ul>                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'arguments passed to init . | ExceptionThatFailsUnpickling'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a wrapper around bytesio that restricts what can be read since data from | FakePayload'</li></ul>                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the network can t be sought and cannot be read outside of its content | FakePayload'</li></ul>                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'length. | FakePayload'</li></ul>                                                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this makes sure that views can t do anything under the test client | FakePayload'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'try to store all messages in the first backend. | FallbackStorage'</li></ul>                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'store any unstored | FallbackStorage'</li></ul>                                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'messages in each subsequent backend. | FallbackStorage'</li></ul>                                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'model added for ticket 19838 | FootNote'</li></ul>                                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests using the french translations of the sampleproject. | FrenchTestCase'</li></ul>                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'table column fields | Group'</li></ul>                                                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'on the accept encoding header. | GZipMiddleware'</li></ul>                                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a widget that splits input into two input type hidden inputs. | HiddenRangeWidget'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'just like the filedescriptor, but for imagefields. | ImageFileDescriptor'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the only difference is | ImageFileDescriptor'</li></ul>                                                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'assigning the width height to the width field height field, if appropriate. | ImageFileDescriptor'</li></ul>                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a form that replaces the model s url field with a custom one. | IncompleteCategoryFormWithExclude'</li></ul>                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a model with a fk to itself. | Individual'</li></ul>                                                                               |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'related instances rendering will be called programmatically in this case . | Individual'</li></ul>                                 |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'no more reads are allowed from this device. | InputStreamExhausted'</li></ul>                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a model s base classes can t be resolved. | InvalidBasesError'</li></ul>                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a minimal hook to produce kml sitemaps. | KMLSitemap'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a base class which provides complete list interface. | ListMixin'</li></ul>                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'derived classes must call listmixin s init function | ListMixin'</li></ul>                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'and implement the following | ListMixin'</li></ul>                                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'function get single external self, i | ListMixin'</li></ul>                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'return single item with index i for general use. | ListMixin'</li></ul>                                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the index i will always satisfy 0 i len self . | ListMixin'</li></ul>                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'function get single internal self, i | ListMixin'</li></ul>                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'same as above, but for use within the class optional | ListMixin'</li></ul>                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'note that if get single internal and get single internal return | ListMixin'</li></ul>                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'different types of objects, set list must distinguish | ListMixin'</li></ul>                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'between the two and handle each appropriately. | ListMixin'</li></ul>                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'function set list self, length, items | ListMixin'</li></ul>                                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'recreate the entire object. | ListMixin'</li></ul>                                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'note items may be a generator which calls get single internal. | ListMixin'</li></ul>                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'therefore, it is necessary to cache the values in a temporary | ListMixin'</li></ul>                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'temp list items | ListMixin'</li></ul>                                                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'before clobbering the original storage. | ListMixin'</li></ul>                                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'function set single self, i, value | ListMixin'</li></ul>                                                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'set the single item at index i to value optional | ListMixin'</li></ul>                                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if left undefined, all mutations will result in rebuilding | ListMixin'</li></ul>                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the object using set list. | ListMixin'</li></ul>                                                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'function len self | ListMixin'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'return the length | ListMixin'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'int minlength | ListMixin'</li></ul>                                                                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the minimum legal length optional | ListMixin'</li></ul>                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'int maxlength | ListMixin'</li></ul>                                                                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the maximum legal length optional | ListMixin'</li></ul>                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'type or tuple allowed | ListMixin'</li></ul>                                                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'a type or tuple of allowed item types optional | ListMixin'</li></ul>                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests for the logout then login view | LogoutThenLoginTests'</li></ul>                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the make list filter can destroy existing escaping, so the results are | MakeListTests'</li></ul>                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'escaped. | MakeListTests'</li></ul>                                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'keep track of how many form instances are displayed on the page. | ManagementForm'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an implementation of a cache binding using python memcached | MemcachedCache'</li></ul>                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'file upload handler to stream uploads into memory used for small files . | MemoryFileUploadHandler'</li></ul>                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the base class for all migrations. | Migration'</li></ul>                                                                          |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'it will have one or more | Migration'</li></ul>                                                                                    |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'of the following attributes | Migration'</li></ul>                                                                                 |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'operations a list of operation instances, probably from django^db.migrations^operations | Migration'</li></ul>                     |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'dependencies a list of tuples of app path, migration name | Migration'</li></ul>                                                   |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'run before a list of tuples of app path, migration name | Migration'</li></ul>                                                     |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'replaces a list of migration names | Migration'</li></ul>                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'represent the digraph of all migrations in a project. | MigrationGraph'</li></ul>                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'each migration is a node, and each dependency is an edge. | MigrationGraph'</li></ul>                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'there are | MigrationGraph'</li></ul>                                                                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'no implicit dependencies between numbered migrations the numbering is | MigrationGraph'</li></ul>                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'merely a convention to aid file listing. | MigrationGraph'</li></ul>                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'migrations files can be marked as replacing another set of migrations | MigrationGraph'</li></ul>                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the graph handler isn t responsible | MigrationGraph'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'migration files and if the replaced migrations are all either unapplied | MigrationGraph'</li></ul>                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'replacing migration, and repoint any dependencies that pointed to the | MigrationGraph'</li></ul>                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'on initialization, this class will scan those directories, and open and | MigrationLoader'</li></ul>                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'inherit from django^db.migrations^migration. | MigrationLoader'</li></ul>                                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'django^db.migrations^migration for what that looks like. | MigrationLoader'</li></ul>                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'these are loaded into a separate set of migrations away from the main ones. | MigrationLoader'</li></ul>                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'disk, then they are injected into the main set, replacing the named migrations. | MigrationLoader'</li></ul>                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'new migration. | MigrationLoader'</li></ul>                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'to disk, but this is probably fine. | MigrationLoader'</li></ul>                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'in memory. | MigrationLoader'</li></ul>                                                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'of the app label^modelname form. | ModelSignal'</li></ul>                                                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'multivaluedict^parse reads the input stream in chunk size chunks | MultiPartParser'</li></ul>                                      |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'and returns a tuple of multivaluedict post , multivaluedict files . | MultiPartParser'</li></ul>                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a subclass of dictionary customized to handle multiple values for the | MultiValueDict'</li></ul>                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'same key. | MultiValueDict'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'d multivaluedict name adrian , simon , position developer | MultiValueDict'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'simon | MultiValueDict'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'d^getlist doesnotexist | MultiValueDict'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'d^get lastname , nonexistent | MultiValueDict'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'nonexistent | MultiValueDict'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'d^setlist lastname , holovaty , willison | MultiValueDict'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'aggregate the logic of multiple fields. | MultiValueField'</li></ul>                                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'its clean method takes a decompressed list of values, which are then | MultiValueField'</li></ul>                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'cleaned into a single value according to self^fields. | MultiValueField'</li></ul>                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'each value in | MultiValueField'</li></ul>                                                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this list is cleaned by the corresponding field the first value is | MultiValueField'</li></ul>                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'cleaned by the first field, the second value is cleaned by the second | MultiValueField'</li></ul>                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'field, etc once all fields are cleaned, the list of clean values is | MultiValueField'</li></ul>                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'compressed into a single value. | MultiValueField'</li></ul>                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a widget that is composed of multiple widgets. | MultiWidget'</li></ul>                                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'in addition to the values added by widget^get context , this widget | MultiWidget'</li></ul>                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'adds a list of subwidgets to the context as widget subwidgets . | MultiWidget'</li></ul>                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'these can be looped over and rendered like normal widgets. | MultiWidget'</li></ul>                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'model subclass with a custom base using metaclass. | MyModel'</li></ul>                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests for nestedobject utility collection. | NestedObjectsTests'</li></ul>                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base class for migration operations. | Operation'</li></ul>                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'it s responsible for both mutating the in memory model state | Operation'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'see db migrations state^py to represent what it performs, as well | Operation'</li></ul>                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'as actually performing it against a live database. | Operation'</li></ul>                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'overwrite existing files instead of appending a suffix to generate an | OverwritingStorage'</li></ul>                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'unused name. | OverwritingStorage'</li></ul>                                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'model where the validation of child foreign key relationships depends | ParentWithDependentChildren'</li></ul>                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'on validation of the parent | ParentWithDependentChildren'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the permissions system provides a way to assign permissions to specific | Permission'</li></ul>                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'users and groups of users. | Permission'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the permission system is used by the django admin site, but may also be | Permission'</li></ul>                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'useful in your own code. | Permission'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the django admin site uses permissions as follows | Permission'</li></ul>                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the add permission limits the user s ability to view the add form | Permission'</li></ul>                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'and add an object. | Permission'</li></ul>                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the change permission limits a user s ability to view the change | Permission'</li></ul>                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'list, view the change form and change an object. | Permission'</li></ul>                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the delete permission limits the ability to delete an object. | Permission'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the view permission limits the ability to view an object. | Permission'</li></ul>                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the permissions listed above are automatically created for each model. | Permission'</li></ul>                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'proxy model inheritance across apps can result in migrate not creating the table | ProxyModelInheritanceTests'</li></ul>           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'for the proxied model as described in #12286 . | ProxyModelInheritanceTests'</li></ul>                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this test creates two dummy | ProxyModelInheritanceTests'</li></ul>                                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'apps and calls migrate, then verifies that the table has been created. | ProxyModelInheritanceTests'</li></ul>                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'you cannot access raw post data from a request that has | RawPostDataException'</li></ul>                                          |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'multipart post data if it has been accessed via post, | RawPostDataException'</li></ul>                                            |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'files, etc. | RawPostDataException'</li></ul>                                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'run tests and record everything but don t display anything. | RemoteTestRunner'</li></ul>                                          |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'regression tests for #8551 and #17067 ensure that environment variables | RequestFactoryEnvironmentTests'</li></ul>                |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'are set correctly in requestfactory. | RequestFactoryEnvironmentTests'</li></ul>                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'accessor to the related objects manager on the one to many relation created | ReverseGenericManyToOneDescriptor'</li></ul>         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'by genericrelation. | ReverseGenericManyToOneDescriptor'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'in the example | ReverseGenericManyToOneDescriptor'</li></ul>                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'class post model | ReverseGenericManyToOneDescriptor'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'comments genericrelation comment | ReverseGenericManyToOneDescriptor'</li></ul>                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'post^comments is a reversegenericmanytoonedescriptor instance. | ReverseGenericManyToOneDescriptor'</li></ul>                      |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'the operator is the same as operator. | SameAsLookup'</li></ul>                                                                    |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'it tests actual geometric | SameAsLookup'</li></ul>                                                                                |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'equality of two features. | SameAsLookup'</li></ul>                                                                                |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'so if a and b are the same feature, | SameAsLookup'</li></ul>                                                                      |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'vertex by vertex, the operator returns true. | SameAsLookup'</li></ul>                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'convert a queryset to json. | Serializer'</li></ul>                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'store messages in the session that is, django^contrib.sessions . | SessionStorage'</li></ul>                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'inside the custom session model. | SessionStore'</li></ul>                                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a simple view with a docstring. | SimpleView'</li></ul>                                                                            |
| tensor([0, 0, 1, 0, 1]) | <ul><li>'spatialrefsys objects to reduce redundant code. | SpatialRefSysMixin'</li></ul>                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a widget that splits datetime input into two input type hidden inputs. | SplitHiddenDateTimeWidget'</li></ul>                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'add a success message on successful form submission. | SuccessMessageMixin'</li></ul>                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the exception used when a template does not exist. | TemplateDoesNotExist'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'optional arguments | TemplateDoesNotExist'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'backend | TemplateDoesNotExist'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'tried | TemplateDoesNotExist'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this | TemplateDoesNotExist'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'is formatted as a list of tuples containing origin, status , where | TemplateDoesNotExist'</li></ul>                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'origin is an origin object or duck type and status is a string with the | TemplateDoesNotExist'</li></ul>                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'reason the template wasn t found. | TemplateDoesNotExist'</li></ul>                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'chain | TemplateDoesNotExist'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a list of intermediate templatedoesnotexist exceptions. | TemplateDoesNotExist'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this is used to | TemplateDoesNotExist'</li></ul>                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'encapsulate multiple exceptions when loading templates from multiple | TemplateDoesNotExist'</li></ul>                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'engines. | TemplateDoesNotExist'</li></ul>                                                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'custom field file class that records whether or not the underlying file | TestImageFieldFile'</li></ul>                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'was opened. | TestImageFieldFile'</li></ul>                                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this doc output is required for testing. | TestUtils'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this is a model that can be used as | UniqueAnchor'</li></ul>                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'something for other models to point at | UniqueAnchor'</li></ul>                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'occurs if django tries to update a session that was deleted. | UpdateError'</li></ul>                                              |
| tensor([0, 1, 0, 0, 1]) | <ul><li>'a form that creates a user, with no privileges, from the given username and | UserCreationForm'</li></ul>                          |
| tensor([0, 1, 0, 0, 1]) | <ul><li>'password. | UserCreationForm'</li></ul>                                                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an adapter class for cursor variables that prevents the wrapped object | VariableWrapper'</li></ul>                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'from being converted into a string when used to instantiate an oracleparam. | VariableWrapper'</li></ul>                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'this can be used generally for any other object that should be passed into | VariableWrapper'</li></ul>                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'cursor^execute as is. | VariableWrapper'</li></ul>                                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'model the frame clause in window expressions. | WindowFrame'</li></ul>                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'there are two types of frame | WindowFrame'</li></ul>                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'clauses which are subclasses, however, all processing and validation by no | WindowFrame'</li></ul>                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'means intended to be complete is done here. | WindowFrame'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests for the x frame options decorators. | XFrameOptionsDecoratorsTests'</li></ul>                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'do not set the header if it s already set or if the response contains | XFrameOptionsMiddleware'</li></ul>                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'a xframe options exempt value set to true. | XFrameOptionsMiddleware'</li></ul>                                                    |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'by default, set the x frame options header to sameorigin , meaning the | XFrameOptionsMiddleware'</li></ul>                        |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'response can only be loaded on a frame within the same site. | XFrameOptionsMiddleware'</li></ul>                                  |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'response from being loaded in a frame in any site, set x frame options in | XFrameOptionsMiddleware'</li></ul>                     |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'your project s django settings to deny . | XFrameOptionsMiddleware'</li></ul>                                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'when this object is returned by an input cell or passed to the | Audio'</li></ul>                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'in the frontend only works in the notebook . | Audio'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'can be one of | Audio'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'numpy 2d array containing waveforms for each channel. | Audio'</li></ul>                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'for the standard channel order, see | Audio'</li></ul>                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'list of float or integer representing the waveform mono | Audio'</li></ul>                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'bytestring containing raw pcm data or | Audio'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if the array option is used, the waveform will be normalized. | Audio'</li></ul>                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'dependent. | Audio'</li></ul>                                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a url to download the data from. | Audio'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'path to a local file to load the data from. | Audio'</li></ul>                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'embed boolean | Audio'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'should the audio data be embedded using a data uri true or should | Audio'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the original source be referenced. | Audio'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set this to true if you want the | Audio'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'audio to playable later with no internet connection in the notebook. | Audio'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default is true , unless the keyword argument url is set, then | Audio'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default value is false . | Audio'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'rate integer | Audio'</li></ul>                                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the sampling rate of the raw data. | Audio'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'only required when data parameter is being used as an array | Audio'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'autoplay bool | Audio'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to true if the audio should immediately start playing. | Audio'</li></ul>                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default is false . | Audio'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'normalize bool | Audio'</li></ul>                                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'whether audio should be normalized rescaled to the maximum possible | Audio'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'range. | Audio'</li></ul>                                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'when set to false , data must be between | Audio'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'1 and 1 inclusive , otherwise an error is raised. | Audio'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'applies only when data is a list or array of samples other types of | Audio'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'audio are never normalized. | Audio'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# generate a sound | Audio'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'import numpy as np | Audio'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'framerate 44100 | Audio'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'t np^linspace 0,5,framerate 5 | Audio'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'audio data,rate framerate | Audio'</li></ul>                                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'dataleft np^sin 2 np^pi 220 t | Audio'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'audio dataleft, dataright ,rate framerate | Audio'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'audio url http www^w3schools^com html horse^ogg | Audio'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'audio filename path to sound^ogg | Audio'</li></ul>                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'audio data b raw wav data. | Audio'</li></ul>                                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'context manager for capturing stdout err | capture_output'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'cross reference role displayed with a %% prefix | CellMagicRole'</li></ul>                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the custom ipython displayhook to replace sys^displayhook. | DisplayHook'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this class does many things, but the basic idea is that it is a callable | DisplayHook'</li></ul>                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'that gets called anytime user code returns a value. | DisplayHook'</li></ul>                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a dummy module used for ipython s interactive module when | DummyMod'</li></ul>                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a namespace must be assigned to the module s dict . | DummyMod'</li></ul>                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'geojson expects json able dict | GeoJSON'</li></ul>                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'transformer for help syntax obj? | HelpEnd'</li></ul>                                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'and obj? | HelpEnd'</li></ul>                                                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'access the history database without adding to it. | HistoryAccessor'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'this is intended for use by standalone history tools. | HistoryAccessor'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'ipython shells use | HistoryAccessor'</li></ul>                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'historymanager, below, which is a subclass of this. | HistoryAccessor'</li></ul>                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'as part of configuring a shell environment. | InteractiveShellApp'</li></ul>                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the following methods should be called by the meth initialize method | InteractiveShellApp'</li></ul>                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'meth init path | InteractiveShellApp'</li></ul>                                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'meth init shell to be implemented by the subclass | InteractiveShellApp'</li></ul>                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'meth init gui pylab | InteractiveShellApp'</li></ul>                                                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'meth init extensions | InteractiveShellApp'</li></ul>                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'meth init code | InteractiveShellApp'</li></ul>                                                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this is used for formatting strings with values that need to be updated | LazyEvaluate'</li></ul>                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'at that time, such as the current time or working directory. | LazyEvaluate'</li></ul>                                             |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'shell functions which can be reached as %function name. | Magics'</li></ul>                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this can make some functions easier to type, eg%cd . | Magics'</li></ul>                                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'vs. %cd . | Magics'</li></ul>                                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'must | Magics'</li></ul>                                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'use the method decorators @line magic and @cell magic to decorate | Magics'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'individual methods as magic functions, and | Magics'</li></ul>                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'use the class decorator @magics class to ensure that the magic | Magics'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'methods are properly registered at the instance level upon instance | Magics'</li></ul>                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'initialization. | Magics'</li></ul>                                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this is myframe. | MyFrame'</li></ul>                                                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'it just shows a few controls on a wxpanel, | MyFrame'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'and has a simple menu. | MyFrame'</li></ul>                                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'namespace to hold arbitrary information. | Obj'</li></ul>                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'subclass of base display hook using coloured prompt | RichPromptDisplayHook'</li></ul>                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'attribute style access. | Struct'</li></ul>                                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'protection of class members like keys, items when using attribute | Struct'</li></ul>                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'style access. | Struct'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the ability to restrict assignment to only existing keys. | Struct'</li></ul>                                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'intelligent merging. | Struct'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'overloaded operators. | Struct'</li></ul>                                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'basic tools used by all traceback printer classes. | TBTools'</li></ul>                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'color escape sequences. | TermColors'</li></ul>                                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'colors in terminals. | TermColors'</li></ul>                                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'string, suitable for defining dummy color schemes in terminals which get | TermColors'</li></ul>                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'confused by color escapes. | TermColors'</li></ul>                                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'placeholder for user defined magics to be added at runtime. | UserMagics'</li></ul>                                                |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'all magics are eventually merged into a single namespace at runtime, but we | UserMagics'</li></ul>                                |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'their own class. | UserMagics'</li></ul>                                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'class for embedding a youtube video in an ipython session, based on its video id. | YouTubeVideo'</li></ul>                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'eg to embed the video from https www^youtube.com watch?v foo , you would | YouTubeVideo'</li></ul>                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'do | YouTubeVideo'</li></ul>                                                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vid youtubevideo foo | YouTubeVideo'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'display vid | YouTubeVideo'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'to start from 30 seconds | YouTubeVideo'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vid youtubevideo abc , start 30 | YouTubeVideo'</li></ul>                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'display vid | YouTubeVideo'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'to calculate seconds from time as hours, minutes, seconds use | YouTubeVideo'</li></ul>                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'class datetime^timedelta | YouTubeVideo'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'start int timedelta hours 1, minutes 46, seconds 40 ^total seconds | YouTubeVideo'</li></ul>                                       |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'other parameters can be provided as documented at | YouTubeVideo'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'https developers^google.com youtube player parameters#parameters | YouTubeVideo'</li></ul>                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'when converting the notebook using nbconvert, a jpeg representation of the video | YouTubeVideo'</li></ul>                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'will be inserted in the document. | YouTubeVideo'</li></ul>                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base mock that pretends to be a poplib pop3 connection. | _MockPOP3'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pm pop3mailbox localhost , user bad , conn cls mockpop3 | _MockPOP3'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | _MockPOP3'</li></ul>                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'accesserror | _MockPOP3'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pm pop3mailbox localhost , user a , password b , | _MockPOP3'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'conn cls mockpop3 | _MockPOP3'</li></ul>                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pm^stat | _MockPOP3'</li></ul>                                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'2, 123456 | _MockPOP3'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pm^iterkeys | _MockPOP3'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'evil , good | _MockPOP3'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'evil in pm, bogon in pm | _MockPOP3'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'true, false | _MockPOP3'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'msg subject for msg in pm | _MockPOP3'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'msg 1 , msg 2 | _MockPOP3'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pm^get msg size evil , pm^get msg size good | _MockPOP3'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'47, 51 | _MockPOP3'</li></ul>                                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pm^get bytes evil | _MockPOP3'</li></ul>                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'from test@mailpile^is nsubject msg 1 n noh, hi! | _MockPOP3'</li></ul>                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'n | _MockPOP3'</li></ul>                                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'from | _MockPOP3'</li></ul>                                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pm invalid key | _MockPOP3'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | _MockPOP3'</li></ul>                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'keyerror . | _MockPOP3'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'search for the autocrypt database. | AutocryptSearch'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this broker tries to auto upgrade connections to use tls, or at | AutoTlsConnBroker'</li></ul>                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'least do the ssl handshake here so we can record info about it. | AutoTlsConnBroker'</li></ul>                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a sanity checking, self documenting dictionary of program settings. | ConfigDict'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the object must be initialized with a dictionary which describes in | ConfigDict'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'a structured way what variables exist, what their legal values are, | ConfigDict'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'and what their defaults are and what they are for. | ConfigDict'</li></ul>                                                         |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'a data type sanity check | ConfigDict'</li></ul>                                                                                   |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'3 | ConfigDict'</li></ul>                                                                                                          |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'a default value | ConfigDict'</li></ul>                                                                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if the sanity check is itself a dictionary of rules, values are expected | ConfigDict'</li></ul>                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this | ConfigDict'</li></ul>                                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'should be used with an empty list or dictionary as a default value. | ConfigDict'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'rules in place of the default value. | ConfigDict'</li></ul>                                                                       |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'if the default value is an empty list, it is assumed to be a list of | ConfigDict'</li></ul>                                       |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'values of the type specified. | ConfigDict'</li></ul>                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>', int , 0 , | ConfigDict'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>', int, 99 , | ConfigDict'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'water liters , int, 0 , | ConfigDict'</li></ul>                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>', | ConfigDict'</li></ul>                                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'x x , str, , , | ConfigDict'</li></ul>                                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sorted pot^keys , sorted pot^values | ConfigDict'</li></ul>                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pot potatoes pot liquids vodka 123 | ConfigDict'</li></ul>                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'123 | ConfigDict'</li></ul>                                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'123 | ConfigDict'</li></ul>                                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'99 | ConfigDict'</li></ul>                                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'123 | ConfigDict'</li></ul>                                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>', vodka | ConfigDict'</li></ul>                                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'0 | ConfigDict'</li></ul>                                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pot colors | ConfigDict'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'0 | ConfigDict'</li></ul>                                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'123 | ConfigDict'</li></ul>                                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | ConfigDict'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | ConfigDict'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | ConfigDict'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | ConfigDict'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'valueerror invalid value for config potatoes moo | ConfigDict'</li></ul>                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | ConfigDict'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'configvalueerror invalid value for config colors 4 green | ConfigDict'</li></ul>                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pot^rules potatoes | ConfigDict'</li></ul>                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'how many potatoes? | ConfigDict'</li></ul>                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>', type int , 0 | ConfigDict'</li></ul>                                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'isinstance pot liquids , configdict | ConfigDict'</li></ul>                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'TRUE | ConfigDict'</li></ul>                                                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'add one or more mailboxes. | ConfigureMailboxes'</li></ul>                                                                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'if not account is specified, the mailbox is only assigned an id for use | ConfigureMailboxes'</li></ul>                            |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'if an account is specified, the mailbox will be assigned to that account | ConfigureMailboxes'</li></ul>                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'connect to a waiting gui o matic gui | ConnectToGuiOMatic'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'set contact lines, ensuring contact exists | ContactSet'</li></ul>                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'encrypteddict which only deals in signed 64 bit int values. | EncryptedIntDict'</li></ul>                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this also adds a working keys function. | EncryptedIntDict'</li></ul>                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'encrypteddict which only deals in unicode values. | EncryptedUnicodeDict'</li></ul>                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this is a single event in the event log. | Event'</li></ul>                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'create forwarding drafts of one or more messages | Forward'</li></ul>                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'view groups | Group_'</li></ul>                                                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'try to collide a hash using the smtorp algorithm | HashCash'</li></ul>                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'list tags | ListTags'</li></ul>                                                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a jinja2 template loader which uses the mailpile configuration | MailpileJinjaLoader'</li></ul>                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'and plugin system to find template files. | MailpileJinjaLoader'</li></ul>                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a maildir class for windows using ! | MailpileMailbox'</li></ul>                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'instead of in filenames | MailpileMailbox'</li></ul>                                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this is a router object that implements the vfs interface but, | MailpileVFS'</li></ul>                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'delegating calls to individual implementations. | MailpileVFS'</li></ul>                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'move an auto tagging rule | MoveFilter'</li></ul>                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a posting list is a map of search terms to message ids. | OldPostingList'</li></ul>                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this combines storagebackeddata with pack unpacklonglist to pack | StorageBackedLongs'</li></ul>                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'storage sbl x01 x00 x00 x00 x00 x00 x00 x00 | StorageBackedLongs'</li></ul>                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sbl storagebackedlongs storage, sbl | StorageBackedLongs'</li></ul>                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'1 in sbl | StorageBackedLongs'</li></ul>                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'TRUE | StorageBackedLongs'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sbl^append 2 | StorageBackedLongs'</li></ul>                                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sbl^save | StorageBackedLongs'</li></ul>                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'unpacklonglist storage sbl 1, 2 | StorageBackedLongs'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'TRUE | StorageBackedLongs'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# vcards are added to the collection using add vcard. | VCardStore'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'this will | VCardStore'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# create a file for the card on disk, using a random name. | VCardStore'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^add vcards mailpilevcard vcardline fn dude , | VCardStore'</li></ul>                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcardline email d@evil^com , | VCardStore'</li></ul>                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'mailpilevcard vcardline fn guy | VCardStore'</li></ul>                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcards can be looked up directly by e mail. | VCardStore'</li></ul>                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^get vcard d@evil^com ^fn | VCardStore'</li></ul>                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'u dude | VCardStore'</li></ul>                                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^get vcard nosuch@email^address is none | VCardStore'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'TRUE | VCardStore'</li></ul>                                                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'or they can be found using searches. | VCardStore'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^find vcards guy 0 ^fn | VCardStore'</li></ul>                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'u guy | VCardStore'</li></ul>                                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'cards can be removed using del vcards | VCardStore'</li></ul>                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^del vcards vcs^get vcard d@evil^com | VCardStore'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^get vcard d@evil^com is none | VCardStore'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'TRUE | VCardStore'</li></ul>                                                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^del vcards vcs^find vcards guy | VCardStore'</li></ul>                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'vcs^find vcards guy | VCardStore'</li></ul>                                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'object serving as a base class for all engines. | AbstractEngine'</li></ul>                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this documenter lets us removes . | AccessorCallableDocumenter'</li></ul>                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'common tests for all variations of intervalindex construction. | Base'</li></ul>                                                   |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'input data | Base'</li></ul>                                                                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'to be supplied in breaks format, then converted by the subclass method | Base'</li></ul>                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'get kwargs from breaks to the expected format. | Base'</li></ul>                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'interface | BaseInterfaceTests'</li></ul>                                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'array of boolean true false data with missing values. | BooleanArray'</li></ul>                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'represented by 2 numpy arrays a boolean array with the data and | BooleanArray'</li></ul>                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'a boolean array with the mask true indicating missing . | BooleanArray'</li></ul>                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'booleanarray implements kleene logic sometimes called three value | BooleanArray'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'below . | BooleanArray'</li></ul>                                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'indicates missing . | BooleanArray'</li></ul>                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'whether to copy the values and mask arrays. | BooleanArray'</li></ul>                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'length 3, dtype boolean | BooleanArray'</li></ul>                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'dateoffset subclass representing possibly n business hours. | BusinessHour'</li></ul>                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'mixin to business types to provide related functions. | BusinessMixin'</li></ul>                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'dateoffset increments between business year begin dates. | BYearBegin'</li></ul>                                                   |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'categories sequence, optional | CategoricalDtype'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'ordered bool or none, default false | CategoricalDtype'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'none can be used to maintain the ordered value of existing categoricals when | CategoricalDtype'</li></ul>                         |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'false if there is no existing ordered to maintain. | CategoricalDtype'</li></ul>                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'categories | CategoricalDtype'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'ordered | CategoricalDtype'</li></ul>                                                                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'notes | CategoricalDtype'</li></ul>                                                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this class is useful for specifying the type of a categorical | CategoricalDtype'</li></ul>                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'independent of the values. | CategoricalDtype'</li></ul>                                                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'see ref categorical^categoricaldtype | CategoricalDtype'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pd^series a , b , a , c , dtype t | CategoricalDtype'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'1 b | CategoricalDtype'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'3 nan | CategoricalDtype'</li></ul>                                                                                                |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'categories 2, object b a | CategoricalDtype'</li></ul>                                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'index based on an underlying class categorical . | CategoricalIndex'</li></ul>                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'categoricalindex, like categorical, can only take on a limited, | CategoricalIndex'</li></ul>                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'also, | CategoricalIndex'</li></ul>                                                                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'like categorical, it might have an order, but numerical operations | CategoricalIndex'</li></ul>                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'additions, divisions, . | CategoricalIndex'</li></ul>                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'are not possible. | CategoricalIndex'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'data array like 1 dimensional | CategoricalIndex'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the values of the categorical. | CategoricalIndex'</li></ul>                                                                       |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'if categories are given, values not in | CategoricalIndex'</li></ul>                                                               |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'categories will be replaced with nan. | CategoricalIndex'</li></ul>                                                                |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'categories index like, optional | CategoricalIndex'</li></ul>                                                                      |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'the categories for the categorical. | CategoricalIndex'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'items need to be unique. | CategoricalIndex'</li></ul>                                                                             |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'if the categories are not given here and also not in dtype , they | CategoricalIndex'</li></ul>                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'will be inferred from the data . | CategoricalIndex'</li></ul>                                                                     |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'ordered bool, optional | CategoricalIndex'</li></ul>                                                                               |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'whether or not this categorical is treated as an ordered | CategoricalIndex'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'categorical. | CategoricalIndex'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if not given here or in dtype , the resulting | CategoricalIndex'</li></ul>                                                        |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'categorical will be unordered. | CategoricalIndex'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'dtype categoricaldtype or category , optional | CategoricalIndex'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if class categoricaldtype , cannot be used together with | CategoricalIndex'</li></ul>                                             |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'categories or ordered . | CategoricalIndex'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'versionadded 021.0 | CategoricalIndex'</li></ul>                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'make a copy of input ndarray. | CategoricalIndex'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'name object, optional | CategoricalIndex'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'name to be stored in the index. | CategoricalIndex'</li></ul>                                                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'codes | CategoricalIndex'</li></ul>                                                                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'categories | CategoricalIndex'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'ordered | CategoricalIndex'</li></ul>                                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'remove unused categories | CategoricalIndex'</li></ul>                                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'set categories | CategoricalIndex'</li></ul>                                                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'as ordered | CategoricalIndex'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'as unordered | CategoricalIndex'</li></ul>                                                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'map | CategoricalIndex'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if the categories do not validate. | CategoricalIndex'</li></ul>                                                                   |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'if an explicit ordered true is given but no categories and the | CategoricalIndex'</li></ul>                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'notes | CategoricalIndex'</li></ul>                                                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'see the user guide | CategoricalIndex'</li></ul>                                                                                   |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'http pandas^pydata.org pandas docs stable user guide advanced^html#categoricalindex | CategoricalIndex'</li></ul>                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pd^categoricalindex a , b , c , a , b , c | CategoricalIndex'</li></ul>                                                            |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'categoricalindex a , b , c , a , b , c , categories a , b , c , ordered false, dtype category # noqa | CategoricalIndex'</li></ul> |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'categoricalindex can also be instantiated from a categorical | CategoricalIndex'</li></ul>                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'c pd^categorical a , b , c , a , b , c | CategoricalIndex'</li></ul>                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pd^categoricalindex c | CategoricalIndex'</li></ul>                                                                                |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'categoricalindex a , b , c , a , b , c , categories a , b , c , ordered false, dtype category # noqa | CategoricalIndex'</li></ul> |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'ordered categoricalindex can have a min and max value. | CategoricalIndex'</li></ul>                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'ci pd^categoricalindex a , b , c , a , b , c , ordered true, | CategoricalIndex'</li></ul>                                         |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'categories c , b , a | CategoricalIndex'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'ci | CategoricalIndex'</li></ul>                                                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'categoricalindex a , b , c , a , b , c , categories c , b , a , ordered true, dtype category # noqa | CategoricalIndex'</li></ul>  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'c | CategoricalIndex'</li></ul>                                                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'custom distutils command subclassed from cython^distutils.build ext | CythonCommand'</li></ul>                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'to compile pyx c, and stop there. | CythonCommand'</li></ul>                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'represent a data column that can be indexed | DataIndexableCol'</li></ul>                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'class for parsing tabular excel sheets into dataframe objects. | ExcelFile'</li></ul>                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'uses xlrd. | ExcelFile'</li></ul>                                                                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'see read excel for more documentation | ExcelFile'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a file like object, xlrd workbook or openpypl workbook. | ExcelFile'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'engine str, default none | ExcelFile'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'acceptable values are none, xlrd , openpyxl or odf . | ExcelFile'</li></ul>                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'class that defines a holiday with start end dates and rules | Holiday'</li></ul>                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'array of integer optional missing values. | IntegerArray'</li></ul>                                                                |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'integerarray is currently experimental, and its api or internal | IntegerArray'</li></ul>                                          |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'we represent an integerarray with 2 numpy arrays | IntegerArray'</li></ul>                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a 1 d integer dtype array. | IntegerArray'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a 1 d boolean dtype array indicating missing values. | IntegerArray'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'whether to copy the values and mask . | IntegerArray'</li></ul>                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'create an integerarray with func pandas^array . | IntegerArray'</li></ul>                                                          |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'int array pd^array 1, none, 3 , dtype pd^int32dtype | IntegerArray'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'int array | IntegerArray'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'1, nan, 3 | IntegerArray'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'length 3, dtype int32 | IntegerArray'</li></ul>                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'string aliases for the dtypes are also available. | IntegerArray'</li></ul>                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'they are capitalized. | IntegerArray'</li></ul>                                                                                    |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'pd^array 1, none, 3 , dtype int32 | IntegerArray'</li></ul>                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'1, nan, 3 | IntegerArray'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'length 3, dtype int32 | IntegerArray'</li></ul>                                                                                    |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'pd^array 1, none, 3 , dtype uint16 | IntegerArray'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'1, nan, 3 | IntegerArray'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'length 3, dtype uint16 | IntegerArray'</li></ul>                                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an extensiondtype for interval data. | IntervalDtype'</li></ul>                                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this is not an actual numpy dtype , but a duck type. | IntervalDtype'</li></ul>                                                    |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'subtype str, np^dtype | IntervalDtype'</li></ul>                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the dtype of the interval bounds. | IntervalDtype'</li></ul>                                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'subtype | IntervalDtype'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'pd^intervaldtype subtype int64 | IntervalDtype'</li></ul>                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'interval int64 | IntervalDtype'</li></ul>                                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'hold methods for the nonconsolidatable blocks | NonConsolidatableMixIn'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 1]) | <ul><li>'make plots of series or dataframe. | PlotAccessor'</li></ul>                                                                       |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'uses the backend specified by the | PlotAccessor'</li></ul>                                                                        |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'by default, matplotlib is used. | PlotAccessor'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'data series or dataframe | PlotAccessor'</li></ul>                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the object for which the method is called. | PlotAccessor'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'x label or position, default none | PlotAccessor'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'only used if data is a dataframe. | PlotAccessor'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'y label, position or list of label, positions, default none | PlotAccessor'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'allows plotting of one column versus another. | PlotAccessor'</li></ul>                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'only used if data is a | PlotAccessor'</li></ul>                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'dataframe. | PlotAccessor'</li></ul>                                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'kind str | PlotAccessor'</li></ul>                                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the kind of plot to produce | PlotAccessor'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'line line plot default | PlotAccessor'</li></ul>                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'bar vertical bar plot | PlotAccessor'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'barh horizontal bar plot | PlotAccessor'</li></ul>                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'hist histogram | PlotAccessor'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'box boxplot | PlotAccessor'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'kde kernel density estimation plot | PlotAccessor'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'density same as kde | PlotAccessor'</li></ul>                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'area area plot | PlotAccessor'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'pie pie plot | PlotAccessor'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'scatter scatter plot | PlotAccessor'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'hexbin hexbin plot. | PlotAccessor'</li></ul>                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'figsize a tuple width, height in inches | PlotAccessor'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'use index bool, default true | PlotAccessor'</li></ul>                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'use index as ticks for x axis. | PlotAccessor'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'title str or list | PlotAccessor'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'title to use for the plot. | PlotAccessor'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if a string is passed, print the string | PlotAccessor'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'at the top of the figure. | PlotAccessor'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if a list is passed and subplots is | PlotAccessor'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'true, print each item in the list above the corresponding subplot. | PlotAccessor'</li></ul>                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'grid bool, default none matlab style default | PlotAccessor'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'axis grid lines. | PlotAccessor'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'legend bool or reverse | PlotAccessor'</li></ul>                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'place legend on axis subplots. | PlotAccessor'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'style list or dict | PlotAccessor'</li></ul>                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the matplotlib line style per column. | PlotAccessor'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'logx bool or sym , default false | PlotAccessor'</li></ul>                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'use log scaling or symlog scaling on x axis. | PlotAccessor'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'versionchanged 025.0 | PlotAccessor'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'logy bool or sym default false | PlotAccessor'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'use log scaling or symlog scaling on y axis. | PlotAccessor'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'versionchanged 025.0 | PlotAccessor'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'loglog bool or sym , default false | PlotAccessor'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'use log scaling or symlog scaling on both x and y axes. | PlotAccessor'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'versionchanged 025.0 | PlotAccessor'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'xticks sequence | PlotAccessor'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'values to use for the xticks. | PlotAccessor'</li></ul>                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'yticks sequence | PlotAccessor'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'values to use for the yticks. | PlotAccessor'</li></ul>                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'xlim 2 tuple list | PlotAccessor'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'ylim 2 tuple list | PlotAccessor'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'rot int, default none | PlotAccessor'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'rotation for ticks xticks for vertical, yticks for horizontal | PlotAccessor'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'fontsize int, default none | PlotAccessor'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'font size for xticks and yticks. | PlotAccessor'</li></ul>                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'colormap str or matplotlib colormap object, default none | PlotAccessor'</li></ul>                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'colormap to select colors from. | PlotAccessor'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if string, load colormap with that | PlotAccessor'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'name from matplotlib. | PlotAccessor'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if true, plot colorbar only relevant for scatter and hexbin | PlotAccessor'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'position float | PlotAccessor'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if true, draw a table using the data in the dataframe and the data | PlotAccessor'</li></ul>                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if a series or dataframe is passed, use passed data to draw a | PlotAccessor'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'yerr dataframe, series, array like, dict and str | PlotAccessor'</li></ul>                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'detail. | PlotAccessor'</li></ul>                                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'equivalent to yerr. | PlotAccessor'</li></ul>                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'when using a secondary y axis, automatically mark the column | PlotAccessor'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'include bool bool, default is false | PlotAccessor'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'backend str, default none | PlotAccessor'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'plotting^backend . | PlotAccessor'</li></ul>                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'alternatively, to | PlotAccessor'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'versionadded 10.0 | PlotAccessor'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'options to pass to matplotlib plotting method. | PlotAccessor'</li></ul>                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'class matplotlib^axes.axes or numpy^ndarray of them | PlotAccessor'</li></ul>                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'will be the object returned by the backend. | PlotAccessor'</li></ul>                                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'notes | PlotAccessor'</li></ul>                                                                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'see matplotlib documentation online for more on this subject | PlotAccessor'</li></ul>                                             |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'center | PlotAccessor'</li></ul>                                                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'implement n largest smallest for series | SelectNSeries'</li></ul>                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'obj series | SelectNSeries'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'n int | SelectNSeries'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'keep first , last , default first | SelectNSeries'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'nordered series | SelectNSeries'</li></ul>                                                                                         |
| tensor([0, 0, 1, 0, 1]) | <ul><li>'this is called to decorate the set operations of intervalindex | SetopCheck'</li></ul>                                             |
| tensor([0, 0, 1, 0, 1]) | <ul><li>'to perform the type check in advance. | SetopCheck'</li></ul>                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'patch the sqltable for fallback support. | SQLiteTable'</li></ul>                                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'instead of a table variable just use the create table statement. | SQLiteTable'</li></ul>                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'for mapping pandas tables to sql tables. | SQLTable'</li></ul>                                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'uses fact that table is reflected by sqlalchemy to | SQLTable'</li></ul>                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'do better type conversions. | SQLTable'</li></ul>                                                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'also holds various flags needed to avoid having to | SQLTable'</li></ul>                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'pass them between functions all the time. | SQLTable'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'warning | StringArray'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'parts of the api may change without warning. | StringArray'</li></ul>                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'values array like | StringArray'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the array of data. | StringArray'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'warning | StringArray'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'currently, this expects an object dtype ndarray | StringArray'</li></ul>                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'where the elements are python strings. | StringArray'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this may | StringArray'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the string methods are available on series backed by | StringArray'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'a stringarray. | StringArray'</li></ul>                                                                                            |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'notes | StringArray'</li></ul>                                                                                                     |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'stringarray returns a booleanarray for comparison methods. | StringArray'</li></ul>                                                |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'pd^array this is , some text , none, data. | StringArray'</li></ul>                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>', dtype string | StringArray'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'stringarray | StringArray'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'this is , some text , na, data. | StringArray'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'values. | StringArray'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'traceback most recent call last | StringArray'</li></ul>                                                                           |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'for comparison methods, this returns a class pandas^booleanarray | StringArray'</li></ul>                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'pd^array a , none, c , dtype string a | StringArray'</li></ul>                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'true, na, false | StringArray'</li></ul>                                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'vectorized string functions for series and index. | StringMethods'</li></ul>                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'nas stay na unless | StringMethods'</li></ul>                                                                                      |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'patterned after python s string | StringMethods'</li></ul>                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'s^str.split | StringMethods'</li></ul>                                                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests specific to intervalindex with datetime like subtype | TestDatetimelikeSubtype'</li></ul>                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests specific to intervalindex^from arrays | TestFromArrays'</li></ul>                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'tests specific to intervalindex^from tuples | TestFromTuples'</li></ul>                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'test periodindex and period series ops consistency | TestPeriodIndexSeriesComparisonConsistency'</li></ul>                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'everything you wanted to test about sorting | TestSorted'</li></ul>                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'error raised when attempting to get a slice of a multiindex, | UnsortedIndexError'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'and the index has not been lexsorted. | UnsortedIndexError'</li></ul>                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'small proxy class that enables external file object | _BZ2Proxy'</li></ul>                                                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'a workaround for a limitation in bz2 module s bz2file | _BZ2Proxy'</li></ul>                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'class which unlike gzip^gzipfile has no support for | _BZ2Proxy'</li></ul>                                                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'a file object argument. | _BZ2Proxy'</li></ul>                                                                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'lazy loading of moved objects | _MovedItems'</li></ul>                                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this object provides sequence like access to the logical ancestors | _PathParents'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'of a path. | _PathParents'</li></ul>                                                                                               |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'requires all given class parseexpression s to be found in the given order. | And'</li></ul>                                        |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'expressions may be separated by whitespace. | And'</li></ul>                                                                       |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'may also be constructed using the operator, which will | And'</li></ul>                                                            |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'suppress backtracking. | And'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'integer word nums | And'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'name expr oneormore word alphas | And'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'expr and integer id ,name expr name ,integer age | And'</li></ul>                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# more easily written as | And'</li></ul>                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'expr integer id name expr name integer age | And'</li></ul>                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'arguments are positional parameters to a command. | Argument'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'they generally | Argument'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'provide fewer features than options but can have infinite nargs | Argument'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'and are required by default. | Argument'</li></ul>                                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'all parameters are passed onwards to the parameter constructor. | Argument'</li></ul>                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'raised if brokenpipeerror occurs for the stdout stream while logging. | BrokenStdoutLoggingError'</li></ul>                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'buckets are used to store the bytecode for one template. | Bucket'</li></ul>                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'it s created | Bucket'</li></ul>                                                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'and initialized by the bytecode cache and passed to the loading functions. | Bucket'</li></ul>                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the buckets get an internal checksum from the cache assigned and use this | Bucket'</li></ul>                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'to automatically reject outdated cache material. | Bucket'</li></ul>                                                               |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'like a macro without a name but a call instead. | CallBlock'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'call is called with | CallBlock'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the unnamed macro as caller argument this node holds. | CallBlock'</li></ul>                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a case insensitive dict like object. | CaseInsensitiveDict'</li></ul>                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'implements all methods and operations of | CaseInsensitiveDict'</li></ul>                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'mutablemapping as well as dict s copy . | CaseInsensitiveDict'</li></ul>                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'also | CaseInsensitiveDict'</li></ul>                                                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'provides lower items . | CaseInsensitiveDict'</li></ul>                                                                            |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'will contain case sensitive keys. | CaseInsensitiveDict'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'however, querying and contains | CaseInsensitiveDict'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'testing is case insensitive | CaseInsensitiveDict'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'cid caseinsensitivedict | CaseInsensitiveDict'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'cid accept application json | CaseInsensitiveDict'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'list cid accept # true | CaseInsensitiveDict'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for example, headers content encoding will return the | CaseInsensitiveDict'</li></ul>                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'value of a content encoding response header, regardless | CaseInsensitiveDict'</li></ul>                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'of how the header name was originally stored. | CaseInsensitiveDict'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'if the constructor, ^update , or equality comparison | CaseInsensitiveDict'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'operations are given keys that have equal ^lower s, the | CaseInsensitiveDict'</li></ul>                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'behavior is undefined. | CaseInsensitiveDict'</li></ul>                                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'enhanced string for len operations on colored output. | ColoredString'</li></ul>                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'raised when there is an error in command line arguments | CommandError'</li></ul>                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a connection error occurred. | ConnectionError'</li></ul>                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'struct in wincon^h. | CONSOLE_SCREEN_BUFFER_INFO'</li></ul>                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the template context holds the variables of a template. | Context_'</li></ul>                                                      |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'creating instances is neither supported nor useful as it s created | Context_'</li></ul>                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'automatically at various stages of the template evaluation and should not | Context_'</li></ul>                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'be created by hand. | Context_'</li></ul>                                                                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'the context is immutable. | Context_'</li></ul>                                                                                    |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'modifications on attr parent must not | Context_'</li></ul>                                                                        |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'happen and modifications on attr vars are allowed from generated | Context_'</li></ul>                                             |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'template code only. | Context_'</li></ul>                                                                                          |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'template filters and global functions marked as | Context_'</li></ul>                                                              |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'func contextfunction s get the active context passed as first argument | Context_'</li></ul>                                       |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'and are allowed to access the context read only. | Context_'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the template context supports read only dict operations get , | Context_'</li></ul>                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'keys , values , items , iterkeys , itervalues , iteritems , | Context_'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'getitem , contains . | Context_'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'additionally there is a meth resolve | Context_'</li></ul>                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'method that doesn t fail with a keyerror but returns an | Context_'</li></ul>                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'class undefined object for missing variables. | Context_'</li></ul>                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a converting tuple wrapper. | ConvertingTuple'</li></ul>                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'there are two cookies that meet the criteria specified in the cookie jar. | CookieConflictError'</li></ul>                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'use ^get and ^set and include domain and path args in order to be more specific. | CookieConflictError'</li></ul>                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a sequence of data views. | DataViewSequence'</li></ul>                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'each entry is an instance of item class . | DataViewSequence'</li></ul>                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a date literal. | Date'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a graph structure with directed edges. | DirectedGraph'</li></ul>                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a base class for distributions, whether installed or from indexes. | Distribution'</li></ul>                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'either way, it must have some metadata, so that s all that s needed | Distribution'</li></ul>                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for construction. | Distribution'</li></ul>                                                                                        |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'globals and others. | Environment'</li></ul>                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'here are the possible initialization parameters | Environment'</li></ul>                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the string marking the beginning of a block. | Environment'</li></ul>                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'defaults to % . | Environment'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the string marking the end of a block. | Environment'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'defaults to % . | Environment'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'variable start string | Environment'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'defaults to . | Environment'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'comment end string | Environment'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the string marking the end of a comment. | Environment'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'line statement prefix | Environment'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'statements. | Environment'</li></ul>                                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'trim blocks | Environment'</li></ul>                                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if this is set to true the first newline after a block is | Environment'</li></ul>                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'removed block, not variable tag! | Environment'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'lstrip blocks | Environment'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'from the start of a line to a block. | Environment'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the sequence that starts a newline. | Environment'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'n or r n . | Environment'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'useful default for linux and os x systems as well as web | Environment'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'keep trailing newline | Environment'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the default is false , which causes a single newline, | Environment'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'versionadded 27 | Environment'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this can either be import paths | Environment'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'for more information have a | Environment'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'should the optimizer be enabled? | Environment'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'undefined | Environment'</li></ul>                                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a callable that can be used to process the result of a variable | Environment'</li></ul>                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'for example one can convert | Environment'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'autoescape | Environment'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default. | Environment'</li></ul>                                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'for more details about autoescaping see | Environment'</li></ul>                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'class jinja2^utils.markup . | Environment'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'as of jinja 24 this can also | Environment'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'be a callable that is passed the template name and has to | Environment'</li></ul>                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'versionchanged 24 | Environment'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'cache size | Environment'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'per default this is 400 which means | Environment'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'1 the cache will not be cleaned. | Environment'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'auto reload | Environment'</li></ul>                                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'sources may change ie file system or database . | Environment'</li></ul>                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if | Environment'</li></ul>                                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'will reload the template. | Environment'</li></ul>                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'for higher performance it s possible to | Environment'</li></ul>                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'disable that. | Environment'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'bytecode cache | Environment'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'cache for the internal jinja bytecode so that templates don t | Environment'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'enable async | Environment'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'you to take advantage of newer python features. | Environment'</li></ul>                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this requires | Environment'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'python 36 or later. | Environment'</li></ul>                                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this usually means the child has exited. | EOF'</li></ul>                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base class for all exceptions raised by this module. | ExceptionPexpect'</li></ul>                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'general exception for extract errors. | ExtractError'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'wrap a list of lines in an object with readline to make | FakeFile'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for example, you could use it to read through a file looking | fdspawn'</li></ul>                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for patterns, or to control a modem or serial device. | fdspawn'</li></ul>                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'usage | FileMetadata'</li></ul>                                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'metadata filemetadata path to pkg info | FileMetadata'</li></ul>                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this provider rejects all data and metadata requests except for pkg info, | FileMetadata'</li></ul>                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the provided location. | FileMetadata'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'usage | FileMetadata'</li></ul>                                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'metadata filemetadata path to pkg info | FileMetadata'</li></ul>                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this provider rejects all data and metadata requests except for pkg info, | FileMetadata'</li></ul>                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the provided location. | FileMetadata'</li></ul>                                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'loads templates from the file system. | FileSystemLoader'</li></ul>                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this loader can find templates | FileSystemLoader'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the loader takes the path to the templates as string, or if multiple | FileSystemLoader'</li></ul>                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'locations are wanted a list of them which is then looked up in the | FileSystemLoader'</li></ul>                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'given order | FileSystemLoader'</li></ul>                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'loader filesystemloader path to templates | FileSystemLoader'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'per default the template encoding is utf 8 which can be changed | FileSystemLoader'</li></ul>                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'by setting the encoding parameter to something else. | FileSystemLoader'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'to follow symbolic links, set the followlinks parameter to true | FileSystemLoader'</li></ul>                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'loader filesystemloader path to templates , followlinks true | FileSystemLoader'</li></ul>                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'lookahead matching of the given parse expression. | FollowedBy'</li></ul>                                                          |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'followedby does not advance the parsing position within | FollowedBy'</li></ul>                                                    |
| tensor([1, 0, 1, 0, 1]) | <ul><li>'expression matches at the current position. | FollowedBy'</li></ul>                                                                |
| tensor([1, 0, 1, 0, 1]) | <ul><li>'followedby | FollowedBy'</li></ul>                                                                                                 |
| tensor([1, 0, 1, 0, 1]) | <ul><li>'always returns a null token list. | FollowedBy'</li></ul>                                                                          |
| tensor([1, 0, 1, 1, 0]) | <ul><li>'if any results names are defined | FollowedBy'</li></ul>                                                                           |
| tensor([1, 0, 1, 1, 0]) | <ul><li>'in the lookahead expression, those will be returned for access by | FollowedBy'</li></ul>                                          |
| tensor([1, 0, 1, 1, 0]) | <ul><li>'name. | FollowedBy'</li></ul>                                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'data word word alphas | FollowedBy'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'attr expr group label suppress oneormore data word, stopon label ^setparseaction ^join | FollowedBy'</li></ul>                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'oneormore attr expr ^parsestring shape square color black posn upper left ^pprint | FollowedBy'</li></ul>                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'prints | FollowedBy'</li></ul>                                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'shape , square , color , black , posn , upper left | FollowedBy'</li></ul>                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'get an attribute or item from an expression that is a ascii only | Getattr'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'bytestring and prefer the attribute. | Getattr'</li></ul>                                                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'the two sbcharsetprobers identify that the text is in | HebrewProber'</li></ul>                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'fact some kind of hebrew, logical or visual. | HebrewProber'</li></ul>                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with the scores of the two sbcharsetprobers to produce a final answer. | HebrewProber'</li></ul>                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'it reduces any sequence of such characters to a single space. | HebrewProber'</li></ul>                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'built. | HebrewProber'</li></ul>                                                                                                   |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'disjointed from the model probers, the results of the hebrewprober | HebrewProber'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'html parser | HTMLParser'</li></ul>                                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'generates a tree structure from a stream of possibly malformed html. | HTMLParser'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an http error occurred. | HTTPError'</li></ul>                                                                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'warned when certain ssl configuration is not available on a platform. | InsecurePlatformWarning'</li></ul>                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'metaclass for all validators | InspectedValidator'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'it reads the metadata contained in pydist^json when it is | InstalledDistribution'</li></ul>                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'instantiated., or uses a passed in metadata instance useful for when | InstalledDistribution'</li></ul>                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'dry run mode is being used . | InstalledDistribution'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an internal name in the compiler. | InternalName'</li></ul>                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'you cannot create these nodes | InternalName'</li></ul>                                                                            |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'yourself but the parser provides a | InternalName'</li></ul>                                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'meth jinja2^parser.parser^free identifier method that creates | InternalName'</li></ul>                                            |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'a new identifier for you. | InternalName'</li></ul>                                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this identifier is not available from the | InternalName'</li></ul>                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'template and is not threated specially by the compiler. | InternalName'</li></ul>                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a date field was improperly specified. | InvalidDateError'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'exception for invalid headers. | InvalidHeaderError'</li></ul>                                                                     |
| tensor([1, 0, 0, 0, 1]) | <ul><li>'an invalid version was found, users should refer to pep 440. | InvalidVersion'</li></ul>                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'unicode set for kanji unicode character range | Kanji'</li></ul>                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'unicode set for katakana unicode character range | Katakana'</li></ul>                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the type of a key. | KeyType'</li></ul>                                                                                            |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'keys can be bare unquoted , or quoted using basic , or literal | KeyType'</li></ul>                                                |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'quotes following the same escaping rules as single line stringtype. | KeyType'</li></ul>                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'lock file creation failed for some other reason. | LockFailed'</li></ul>                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'raise lockfailed | LockFailed'</li></ul>                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'except lockerror | LockFailed'</li></ul>                                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a simple lru cache implementation. | LRUCache'</li></ul>                                                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this is fast for small capacities something below 1000 but doesn t | LRUCache'</li></ul>                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'scale. | LRUCache'</li></ul>                                                                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'but as long as it s only used as storage for templates this | LRUCache'</li></ul>                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'won t do any harm. | LRUCache'</li></ul>                                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a string that is ready to be safely inserted into an html or xml | Markup'</li></ul>                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'document, either because it was escaped or because it was marked | Markup'</li></ul>                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'safe. | Markup'</li></ul>                                                                                                          |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'passing an object to the constructor converts it to text and wraps | Markup'</li></ul>                                             |
| tensor([1, 1, 0, 1, 0]) | <ul><li>'to escape the text, use the | Markup'</li></ul>                                                                                    |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'this implements the html interface that some frameworks | Markup'</li></ul>                                                        |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'passing an object that implements html will wrap the | Markup'</li></ul>                                                           |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'all methods escape their arguments and return a markup instance. | Markup'</li></ul>                                               |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'markup em foo &amp bar em | Markup'</li></ul>                                                                                      |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'markup em hello em &lt foo&gt | Markup'</li></ul>                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this class implements a bytecode cache that uses a memcache cache for | MemcachedBytecodeCache'</li></ul>                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'it does not enforce a specific memcache library | MemcachedBytecodeCache'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'tummy s memcache or cmemcache but will accept any class that provides | MemcachedBytecodeCache'</li></ul>                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the minimal interface required. | MemcachedBytecodeCache'</li></ul>                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the minimal interface for the client passed to the constructor is this | MemcachedBytecodeCache'</li></ul>                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'method set key, value , timeout | MemcachedBytecodeCache'</li></ul>                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'value is a string and | MemcachedBytecodeCache'</li></ul>                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'if timeout is not provided | MemcachedBytecodeCache'</li></ul>                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'provided it s an integer with the number of seconds the cache | MemcachedBytecodeCache'</li></ul>                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'method get key | MemcachedBytecodeCache'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'if the item does not | MemcachedBytecodeCache'</li></ul>                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'memoized zipfile manifests. | MemoizedZipManifests'</li></ul>                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a required metadata is missing | MetadataMissingError'</li></ul>                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'dict with 2 special properties | MethodDispatcher'</li></ul>                                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'on initiation, keys that are lists, sets or tuples are converted to | MethodDispatcher'</li></ul>                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'multiple keys so accessing any one of the items in the original | MethodDispatcher'</li></ul>                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'list like object returns the matching value | MethodDispatcher'</li></ul>                                                          |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'a default value which can be set through the default attribute. | MethodDispatcher'</li></ul>                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'lazy loading of moved objects in six^moves.urllib parse | Module_six_moves_urllib_parse'</li></ul>                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'lazy loading of moved objects in six^moves.urllib request | Module_six_moves_urllib_request'</li></ul>                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'lazy loading of moved objects in six^moves.urllib response | Module_six_moves_urllib_response'</li></ul>                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'multiplies the left with the right node. | Mul'</li></ul>                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an environment that renders templates to native python types. | NativeEnvironment'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'represents an item in the tree | Node'</li></ul>                                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a token that will never match. | NoMatch'</li></ul>                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'lookahead to disallow matching with the given parse expression. | NotAny'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'notany does not advance the parsing position within the | NotAny'</li></ul>                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'input string, it only verifies that the specified parse expression | NotAny'</li></ul>                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'does not match at the current position. | NotAny'</li></ul>                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'also, notany does | NotAny'</li></ul>                                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'not skip over leading whitespace. | NotAny'</li></ul>                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'a null token list. | NotAny'</li></ul>                                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# take care not to mistake keywords for identifiers | NotAny'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'boolean term optional not ident | NotAny'</li></ul>                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# operation hierarchy, use infixnotation | NotAny'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# integers that are followed by . | NotAny'</li></ul>                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'integer word nums char . | NotAny'</li></ul>                                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'raised when an attempt is made to unlock a file someone else locked. | NotMyLock'</li></ul>                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'raise notmylock | NotMyLock'</li></ul>                                                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'ordered multivalue dictionary. | omdict'</li></ul>                                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a multivalue dictionary is a dictionary that can store multiple values per | omdict'</li></ul>                                     |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'key. | omdict'</li></ul>                                                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'an ordered multivalue dictionary is a multivalue dictionary that | omdict'</li></ul>                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'retains the order of insertions and deletions. | omdict'</li></ul>                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'internally, items are stored in a doubly linked list, self. | omdict'</li></ul>                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'items. | omdict'</li></ul>                                                                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'a | omdict'</li></ul>                                                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'dictionary, self. | omdict'</li></ul>                                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'map, is also maintained and stores an ordered list of | omdict'</li></ul>                                                          |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'linked list node references, one for each value associated with that key. | omdict'</li></ul>                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'standard dict methods interact with the first value associated with a given | omdict'</li></ul>                                    |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'key. | omdict'</li></ul>                                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this means that omdict retains method parity with dict, and a dict | omdict'</li></ul>                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'object can be replaced with an omdict object and all interaction will | omdict'</li></ul>                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'behave identically. | omdict'</li></ul>                                                                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'all dict methods that retain parity with omdict are | omdict'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'clear , copy , update , fromkeys , len | omdict'</li></ul>                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'items , keys , values , iteritems , iterkeys , itervalues , | omdict'</li></ul>                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'added parameters are optional, existing use remains unaffected. | omdict'</li></ul>                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'key parameter has been added to these methods | omdict'</li></ul>                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'new methods have also been added to omdict. | omdict'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'methods with list in their | omdict'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'name interact with lists of values, and methods with all in their name | omdict'</li></ul>                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'interact with all items in the dictionary, including multiple items with | omdict'</li></ul>                                       |
| tensor([1, 0, 0, 1, 1]) | <ul><li>'the same key. | omdict'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the new omdict methods are | omdict'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'load , size , reverse , | omdict'</li></ul>                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'getlist , add , addlist , set , setlist , setdefaultlist , | omdict'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'poplist , popvalue , popvalues , popitem , poplistitem , | omdict'</li></ul>                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'allitems , allkeys , allvalues , lists , listitems , | omdict'</li></ul>                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'iterallitems , iterallkeys , iterallvalues , iterlists , | omdict'</li></ul>                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'iterlistitems | omdict'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'options are usually optional values on the command line and | Option'</li></ul>                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'have some extra features that arguments don t have. | Option'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'all other parameters are passed onwards to the parameter constructor. | Option'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param show default controls if the default value should be shown on the | Option'</li></ul>                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'help page. | Option'</li></ul>                                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'normally, defaults are not shown. | Option'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if this | Option'</li></ul>                                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'value is a string, it shows the string instead of the | Option'</li></ul>                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'value. | Option'</li></ul>                                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this is particularly useful for dynamic options. | Option'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param show envvar controls if an environment variable should be shown on | Option'</li></ul>                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'normally, environment variables | Option'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'are not shown. | Option'</li></ul>                                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param prompt if set to true or a non empty string then the user will be | Option'</li></ul>                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'prompted for input. | Option'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if set to true the prompt will be the | Option'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'option name capitalized. | Option'</li></ul>                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param confirmation prompt if set then the value will need to be confirmed | Option'</li></ul>                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if it was prompted for. | Option'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'hidden from the user. | Option'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this is useful for password | Option'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'input. | Option'</li></ul>                                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param is flag forces this option to act as a flag. | Option'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the default is | Option'</li></ul>                                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'auto detection. | Option'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param flag value which value should be used for this flag if it s | Option'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'enabled. | Option'</li></ul>                                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this is set to a boolean automatically if | Option'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the option string contains a slash to mark two options. | Option'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param multiple if this is set to true then the argument is accepted | Option'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'multiple times and recorded. | Option'</li></ul>                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this is similar to nargs | Option'</li></ul>                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'in how it works but supports arbitrary number of | Option'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'arguments. | Option'</li></ul>                                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param count this flag makes an option increment an integer. | Option'</li></ul>                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param allow from autoenv if this is enabled then the value of this | Option'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'parameter will be pulled from an environment | Option'</li></ul>                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'variable in case a prefix is defined on the | Option'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'context. | Option'</li></ul>                                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param help the help string. | Option'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param hidden hide this option from help outputs. | Option'</li></ul>                                                               |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'this wrapper is used to catch and suppress brokenpipeerrors resulting | PacifyFlushWrapper'</li></ul>                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'other cleanup code, and the case where the underlying file is not a broken | PacifyFlushWrapper'</li></ul>                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'pipe, all calls and attributes are proxied. | PacifyFlushWrapper'</li></ul>                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'represents a package index and provides easier access to endpoints | PackageIndex'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this error occurs when the parser encounters a syntax error | ParseError'</li></ul>                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'in the toml being parsed. | ParseError'</li></ul>                                                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'is found stops all parsing immediately | ParseFatalException'</li></ul>                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'abstract base level parser element class. | ParserElement'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'compatibility shim for the urlparse^parseresultbytes object. | ParseResultBytes'</li></ul>                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'structured parse results, to provide multiple means of access to | ParseResults'</li></ul>                                         |
| tensor([1, 0, 0, 0, 1]) | <ul><li>'the parsed data | ParseResults'</li></ul>                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'as a list len results | ParseResults'</li></ul>                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'by list index results 0 , results 1 , etc | ParseResults'</li></ul>                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'by attribute results. | ParseResults'</li></ul>                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'resultsname see class parserelement^setresultsname | ParseResults'</li></ul>                                                       |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'integer word nums | ParseResults'</li></ul>                                                                                        |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'date str integer^setresultsname year | ParseResults'</li></ul>                                                                     |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'integer^setresultsname month | ParseResults'</li></ul>                                                                             |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'integer^setresultsname day | ParseResults'</li></ul>                                                                               |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'# equivalent form | ParseResults'</li></ul>                                                                                        |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'# date str integer year integer month integer day | ParseResults'</li></ul>                                                        |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'# parsestring returns a parseresults object | ParseResults'</li></ul>                                                              |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'result date str^parsestring 1999 12 31 | ParseResults'</li></ul>                                                                   |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'def test s, fn repr | ParseResults'</li></ul>                                                                                      |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'print %s %s % s, fn eval s | ParseResults'</li></ul>                                                                               |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'test list result | ParseResults'</li></ul>                                                                                         |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'test result 0 | ParseResults'</li></ul>                                                                                            |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'test result month | ParseResults'</li></ul>                                                                                        |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'test result^day | ParseResults'</li></ul>                                                                                          |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'test month in result | ParseResults'</li></ul>                                                                                     |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'test minutes in result | ParseResults'</li></ul>                                                                                   |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'test result^dump , str | ParseResults'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'prints | ParseResults'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'list result 1999 , , 12 , , 31 | ParseResults'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'result 0 1999 | ParseResults'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'result month 12 | ParseResults'</li></ul>                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'result^day 31 | ParseResults'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'month in result true | ParseResults'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'minutes in result false | ParseResults'</li></ul>                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'result^dump 1999 , , 12 , , 31 | ParseResults'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'day 31 | ParseResults'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'month 12 | ParseResults'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'year 1999 | ParseResults'</li></ul>                                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'different checks. | Path'</li></ul>                                                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'first of all, instead of returning an open file | Path'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param exists if set to true, the file or directory needs to exist for | Path'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this value to be valid. | Path'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if this is not required and a | Path'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'file does indeed not exist, then all further checks are | Path'</li></ul>                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'silently skipped. | Path'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'it | Path'</li></ul>                                                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'will not expand a tilde prefix, as this is | Path'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'supposed to be done by the shell only. | Path'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param allow dash if this is set to true , a single dash to indicate | Path'</li></ul>                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'allows for arbitrary requests while transparently keeping track of | PoolManager'</li></ul>                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'explicitly. | PoolManager'</li></ul>                                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'class urllib3^connectionpool.connectionpool instances. | PoolManager'</li></ul>                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'manager poolmanager num pools 2 | PoolManager'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'r manager^request get , http yahoo^com | PoolManager'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a loader that is passed a dict of loaders where each loader is bound | PrefixLoader'</li></ul>                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'to a prefix. | PrefixLoader'</li></ul>                                                                                             |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'the prefix is delimited from the template by a slash per | PrefixLoader'</li></ul>                                                 |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'default, which can be changed by setting the delimiter argument to | PrefixLoader'</li></ul>                                       |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'something else | PrefixLoader'</li></ul>                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'loader prefixloader | PrefixLoader'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'app1 packageloader mypackage^app1 , | PrefixLoader'</li></ul>                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'by loading app1 index^html the file from the app1 package is loaded, | PrefixLoader'</li></ul>                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'holds a jinja preprocessed traceback for printing or reraising. | ProcessedTraceback'</li></ul>                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this locator uses pypi s json interface. | PyPIJSONLocator'</li></ul>                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'raised when an archive cannot be read | ReadError'</li></ul>                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a user created class request request object. | Request'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param method http method to use. | Request'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param url url to send. | Request'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param headers dictionary of headers to send. | Request'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param files dictionary of filename fileobject files to multipart upload. | Request'</li></ul>                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param data the body to attach to the request. | Request'</li></ul>                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if a dictionary or | Request'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'list of tuples key, value is provided, form encoding will | Request'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'take place. | Request'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param json json for the body to attach to the request if files or data is not specified . | Request'</li></ul>                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param params url parameters to append to the url. | Request'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if a dictionary or | Request'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'list of tuples key, value is provided, form encoding will | Request'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'take place. | Request'</li></ul>                                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param auth auth handler or user, pass tuple. | Request'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param cookies dictionary or cookiejar of cookies to attach to this request. | Request'</li></ul>                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'usage | Request'</li></ul>                                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'req requests^request get , https httpbin^org get | Request'</li></ul>                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'preparedrequest get | Request'</li></ul>                                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'raised when a general error occurs parsing a requirements file line. | RequirementsFileParseError'</li></ul>                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a context manager to remove a package for the inner block. | RequirementUninstaller'</li></ul>                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this uses uninstallpathset to control the workflow. | RequirementUninstaller'</li></ul>                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if the inner block | RequirementUninstaller'</li></ul>                                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'exits correctly, the uninstallation is committed, otherwise rolled back. | RequirementUninstaller'</li></ul>                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'cache a candidate s requires python information. | RequiresPythonCache'</li></ul>                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a class representing an in package resource, such as a data file. | Resource'</li></ul>                                            |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this is | Resource'</li></ul>                                                                                                      |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'not normally instantiated by user code, but rather by a | Resource'</li></ul>                                                      |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'class resourcefinder which manages the resource. | Resource'</li></ul>                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'resource finder for file system resources. | ResourceFinder'</li></ul>                                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'manage resource extraction and packages | ResourceManager'</li></ul>                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'response needs to be chunked in order to read it as chunks. | ResponseNotChunked'</li></ul>                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'retry configuration. | Retry'</li></ul>                                                                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'each retry attempt will create a new retry object with updated values, so | Retry'</li></ul>                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'they can be safely reused. | Retry'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'retries can be defined as a default for a pool | Retry'</li></ul>                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'retries retry connect 5, read 2, redirect 5 | Retry'</li></ul>                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'response http^request get , http example^com | Retry'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'retries can be disabled by passing false | Retry'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param int total | Retry'</li></ul>                                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'total number of retries to allow. | Retry'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'takes precedence over other counts. | Retry'</li></ul>                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to none to remove this constraint and fall back on other | Retry'</li></ul>                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'counts. | Retry'</li></ul>                                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'it s a good idea to set this to some sensibly high value to | Retry'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'account for unexpected edge cases and avoid infinite retry loops. | Retry'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to 0 to fail on the first retry. | Retry'</li></ul>                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to false to disable and imply raise on redirect false . | Retry'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param int connect | Retry'</li></ul>                                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'how many connection related errors to retry on. | Retry'</li></ul>                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'these are errors raised before the request is sent to the remote server, | Retry'</li></ul>                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to 0 to fail on the first retry of this type. | Retry'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param int read | Retry'</li></ul>                                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'how many times to retry on read errors. | Retry'</li></ul>                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'these errors are raised after the request was sent to the server, so the | Retry'</li></ul>                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'request may have side effects. | Retry'</li></ul>                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to 0 to fail on the first retry of this type. | Retry'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param int redirect | Retry'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'how many redirects to perform. | Retry'</li></ul>                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'limit this to avoid infinite redirect | Retry'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'loops. | Retry'</li></ul>                                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a redirect is a http response with a status code 301, 302, 303, 307 or | Retry'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'308 | Retry'</li></ul>                                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to 0 to fail on the first retry of this type. | Retry'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to false to disable and imply raise on redirect false . | Retry'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param int status | Retry'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'how many times to retry on bad status codes. | Retry'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'these are retries made on responses, where status code matches | Retry'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'status forcelist . | Retry'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to 0 to fail on the first retry of this type. | Retry'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param iterable method whitelist | Retry'</li></ul>                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set of uppercased http method verbs that we should retry on. | Retry'</li></ul>                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'by default, we only retry on methods which are considered to be | Retry'</li></ul>                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'idempotent multiple requests with the same parameters end with the | Retry'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'same state . | Retry'</li></ul>                                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'see attr retry^default method whitelist . | Retry'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'set to a false value to retry on any verb. | Retry'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param iterable status forcelist | Retry'</li></ul>                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a set of integer http status codes that we should force a retry on. | Retry'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a retry is initiated if the request method is in method whitelist | Retry'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'by default, this is disabled with none . | Retry'</li></ul>                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param float backoff factor | Retry'</li></ul>                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'a backoff factor to apply between attempts after the second try | Retry'</li></ul>                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'most errors are resolved immediately by a second try without a | Retry'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'delay . | Retry'</li></ul>                                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'urllib3 will sleep for | Retry'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'backoff factor 2 number of total retries 1 | Retry'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'seconds. | Retry'</li></ul>                                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if the backoff factor is 01, then func ^sleep will sleep | Retry'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'for 00s, 02s, 04s, . | Retry'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'between retries. | Retry'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'it will never be longer | Retry'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'than attr retry^backoff max . | Retry'</li></ul>                                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'by default, backoff is disabled set to 0 . | Retry'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param bool raise on redirect whether, if the number of redirects is | Retry'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'exhausted, to raise a maxretryerror, or to return a response with a | Retry'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'response code in the 3xx range. | Retry'</li></ul>                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param bool raise on status similar meaning to raise on redirect | Retry'</li></ul>                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'whether we should raise an exception, or return a response, | Retry'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if status falls in status forcelist range and retries have | Retry'</li></ul>                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'been exhausted. | Retry'</li></ul>                                                                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param tuple history the history of the request encountered during | Retry'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'each call to meth retry^increment . | Retry'</li></ul>                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the list is in the order | Retry'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the requests occurred. | Retry'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'each list item is of class class requesthistory . | Retry'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param bool respect retry after header | Retry'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'whether to respect retry after header on status codes defined as | Retry'</li></ul>                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'attr retry^retry after status codes or not. | Retry'</li></ul>                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'param iterable remove headers on redirect | Retry'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'sequence of headers to remove from the request when a response | Retry'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'indicating a redirect is returned before firing off the redirected | Retry'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'request. | Retry'</li></ul>                                                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a file based cache which is safe to use even when the target directory may | SafeFileCache'</li></ul>                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'not be accessible or writable. | SafeFileCache'</li></ul>                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this validator mixin provides mechanics to validate schemas passed to a cerberus | SchemaValidatorMixin'</li></ul>                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'validator. | SchemaValidatorMixin'</li></ul>                                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a requests session. | Session'</li></ul>                                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'provides cookie persistence, connection pooling, and configuration. | Session'</li></ul>                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'basic usage | Session'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'s requests^session | Session'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'s^get https httpbin^org get | Session'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'response 200 | Session'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'or as a context manager | Session'</li></ul>                                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with requests^session as s | Session'</li></ul>                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'s^get https httpbin^org get | Session'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'response 200 | Session'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'token for skipping over all undefined text until the matched | SkipTo'</li></ul>                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'expression is found. | SkipTo'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'expr target expression marking the end of the data to be skipped | SkipTo'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'include default false if true, the target expression is also parsed | SkipTo'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the skipped text and target expression are returned as a 2 element list . | SkipTo'</li></ul>                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'ignore default none used to define grammars typically quoted strings and | SkipTo'</li></ul>                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'comments that might contain false matches to the target expression | SkipTo'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'failon default none define expressions that are not allowed to be | SkipTo'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'included in the skipped test if found before the target expression is found, | SkipTo'</li></ul>                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the skipto is not a match | SkipTo'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'report | SkipTo'</li></ul>                                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# severity description days open | SkipTo'</li></ul>                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'101 critical intermittent system crash 6 | SkipTo'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'94 cosmetic spelling error on login log n 14 | SkipTo'</li></ul>                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'integer word nums | SkipTo'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sep suppress | SkipTo'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# use skipto to simply match everything up until the next sep | SkipTo'</li></ul>                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# ignore quoted strings, so that a character inside a quoted string does not match | SkipTo'</li></ul>                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# parse action will call token^strip for each matched token, ie, the description body | SkipTo'</li></ul>                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'string data skipto sep, ignore quotedstring | SkipTo'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'string data^setparseaction tokenmap str^strip | SkipTo'</li></ul>                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'ticket expr integer issue num sep | SkipTo'</li></ul>                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'string data sev sep | SkipTo'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'string data desc sep | SkipTo'</li></ul>                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'integer days open | SkipTo'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'print tkt^dump | SkipTo'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'prints | SkipTo'</li></ul>                                                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'101 , critical , intermittent system crash , 6 | SkipTo'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'days open 6 | SkipTo'</li></ul>                                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'desc intermittent system crash | SkipTo'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'issue num 101 | SkipTo'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sev critical | SkipTo'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'94 , cosmetic , spelling error on login log n , 14 | SkipTo'</li></ul>                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'days open 14 | SkipTo'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'desc spelling error on login log n | SkipTo'</li></ul>                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'issue num 94 | SkipTo'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sev cosmetic | SkipTo'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'days open 47 | SkipTo'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'issue num 79 | SkipTo'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'sev minor | SkipTo'</li></ul>                                                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'token class. | Token'</li></ul>                                                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'iterate over the stream | TokenStreamIterator'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'documentclass the class to use for the bottommost node of a document | TreeBuilder'</li></ul>                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'elementclass the class to use for html elements | TreeBuilder'</li></ul>                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'commentclass the class to use for comments | TreeBuilder'</li></ul>                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'doctypeclass the class to use for doctypes | TreeBuilder'</li></ul>                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'abstract base class for tries | Trie'</li></ul>                                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base class for errors arising from attempts to release the lock. | UnlockError'</li></ul>                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'raise unlockerror | UnlockError'</li></ul>                                                                                         |
| tensor([1, 0, 1, 0, 1]) | <ul><li>'an op namespace to dynamically bind operators into python. | _OpNamespace'</li></ul>                                               |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'to | _OpNamespace'</li></ul>                                                                                                       |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'instead, the | _OpNamespace'</li></ul>                                                                                             |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'on the torch^ops object, which will create a new opnamespace | _OpNamespace'</li></ul>                                             |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'torch^ops.my namespace^my op will then invoke getattr on | _OpNamespace'</li></ul>                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'torch^get operation , a function bound from c , and then in a similar | _OpNamespace'</li></ul>                                    |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'3 | _OpNamespace'</li></ul>                                                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'torch^ops.my namespace^my op . | _OpNamespace'</li></ul>                                                                           |
| tensor([1, 0, 1, 0, 0]) | <ul><li>'operation will already exist . | _OpNamespace'</li></ul>                                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'implements adadelta algorithm. | Adadelta'</li></ul>                                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'it has been proposed in adadelta an adaptive learning rate method . | Adadelta'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'arguments | Adadelta'</li></ul>                                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'of squared gradients default 09 | Adadelta'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'numerical stability default 1e 6 | Adadelta'</li></ul>                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'to the parameters default 10 | Adadelta'</li></ul>                                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'implements adam algorithm. | Adam'</li></ul>                                                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'it has been proposed in adam a method for stochastic optimization . | Adam'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'arguments | Adam'</li></ul>                                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'lr float, optional learning rate default 1e 3 | Adam'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'running averages of gradient and its square default 09, 0999 | Adam'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default false | Adam'</li></ul>                                                                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'adam a method for stochastic optimization | Adam'</li></ul>                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'https arxiv^org abs 14126980 | Adam'</li></ul>                                                                                     |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'on the convergence of adam and beyond | Adam'</li></ul>                                                                            |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'https openreview^net forum?id ryqu7f rz | Adam'</li></ul>                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'it has been proposed in adam a method for stochastic optimization . | Adamax'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'arguments | Adamax'</li></ul>                                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'lr float, optional learning rate default 2e 3 | Adamax'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'running averages of gradient and its square | Adamax'</li></ul>                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'applies a 3d adaptive max pooling over an input signal composed of several input planes. | AdaptiveMaxPool3d'</li></ul>            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the output is of size d x h x w, for any input size. | AdaptiveMaxPool3d'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the number of output features is equal to the number of input planes. | AdaptiveMaxPool3d'</li></ul>                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'output size the target output size of the image of the form d x h x w. | AdaptiveMaxPool3d'</li></ul>                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'can be a tuple d, h, w or a single d for a cube d x d x d. | AdaptiveMaxPool3d'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'d, h and w can be either a int , or none which means the size will | AdaptiveMaxPool3d'</li></ul>                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'be the same as that of the input. | AdaptiveMaxPool3d'</li></ul>                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'return indices if true , will return the indices along with the outputs. | AdaptiveMaxPool3d'</li></ul>                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'useful to pass to nn^maxunpool3d. | AdaptiveMaxPool3d'</li></ul>                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default false | AdaptiveMaxPool3d'</li></ul>                                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# target output size of 5x7x9 | AdaptiveMaxPool3d'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m nn^adaptivemaxpool3d 5,7,9 | AdaptiveMaxPool3d'</li></ul>                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'input torch^randn 1, 64, 8, 9, 10 | AdaptiveMaxPool3d'</li></ul>                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output m input | AdaptiveMaxPool3d'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# target output size of 7x7x7 cube | AdaptiveMaxPool3d'</li></ul>                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m nn^adaptivemaxpool3d 7 | AdaptiveMaxPool3d'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'input torch^randn 1, 64, 10, 9, 8 | AdaptiveMaxPool3d'</li></ul>                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output m input | AdaptiveMaxPool3d'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# target output size of 7x9x8 | AdaptiveMaxPool3d'</li></ul>                                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'input torch^randn 1, 64, 10, 9, 8 | AdaptiveMaxPool3d'</li></ul>                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output m input | AdaptiveMaxPool3d'</li></ul>                                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base class used for all tensorboard tests | BaseTestCase'</li></ul>                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'applies batch normalization over a 2d or 3d input a mini batch of 1d | BatchNorm1d'</li></ul>                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'inputs with optional additional channel dimension as described in the paper | BatchNorm1d'</li></ul>                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'batch normalization accelerating deep network training by reducing internal covariate shift . | BatchNorm1d'</li></ul>             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the mean and standard deviation are calculated per dimension over | BatchNorm1d'</li></ul>                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'of size c where c is the input size . | BatchNorm1d'</li></ul>                                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'computed mean and variance, which are then used for normalization during | BatchNorm1d'</li></ul>                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the running estimates are kept with a default attr momentum | BatchNorm1d'</li></ul>                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'of 01. | BatchNorm1d'</li></ul>                                                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'evaluation time as well. | BatchNorm1d'</li></ul>                                                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'because the batch normalization is done over the c dimension, computing statistics | BatchNorm1d'</li></ul>                        |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'num features math c from an expected input of size | BatchNorm1d'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'eps a value added to the denominator for numerical stability. | BatchNorm1d'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default 1e 5 | BatchNorm1d'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'momentum the value used for the running mean and running var | BatchNorm1d'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'computation. | BatchNorm1d'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'can be set to none for cumulative moving average | BatchNorm1d'</li></ul>                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'ie simple average . | BatchNorm1d'</li></ul>                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default 01 | BatchNorm1d'</li></ul>                                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'affine a boolean value that when set to true , this module has | BatchNorm1d'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'learnable affine parameters. | BatchNorm1d'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default true | BatchNorm1d'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'track running stats a boolean value that when set to true , this | BatchNorm1d'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'module tracks the running mean and variance, and when set to false , | BatchNorm1d'</li></ul>                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'this module does not track such statistics and always uses batch | BatchNorm1d'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'statistics in both training and eval modes. | BatchNorm1d'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default true | BatchNorm1d'</li></ul>                                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'input math n, c or math n, c, l | BatchNorm1d'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# with learnable parameters | BatchNorm1d'</li></ul>                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m nn^batchnorm1d 100 | BatchNorm1d'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# without learnable parameters | BatchNorm1d'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'input torch^randn 20, 100 | BatchNorm1d'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output m input | BatchNorm1d'</li></ul>                                                                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this loss combines a sigmoid layer and the bceloss in one single | BCEWithLogitsLoss'</li></ul>                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'class. | BCEWithLogitsLoss'</li></ul>                                                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this version is more numerically stable than using a plain sigmoid | BCEWithLogitsLoss'</li></ul>                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'followed by a bceloss as, by combining the operations into one layer, | BCEWithLogitsLoss'</li></ul>                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'we take advantage of the log sum exp trick for numerical stability. | BCEWithLogitsLoss'</li></ul>                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the unreduced ie with attr reduction set to none loss can be described as | BCEWithLogitsLoss'</li></ul>                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if attr reduction is not none | BCEWithLogitsLoss'</li></ul>                                                                       |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'default mean , then | BCEWithLogitsLoss'</li></ul>                                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'ell x, y begin cases | BCEWithLogitsLoss'</li></ul>                                                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'operatorname mean l , & text if reduction text mean | BCEWithLogitsLoss'</li></ul>                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'operatorname sum l , & text if reduction text sum . | BCEWithLogitsLoss'</li></ul>                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'end cases | BCEWithLogitsLoss'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this is used for measuring the error of a reconstruction in for example | BCEWithLogitsLoss'</li></ul>                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'an auto encoder. | BCEWithLogitsLoss'</li></ul>                                                                                    |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'note that the targets t i should be numbers | BCEWithLogitsLoss'</li></ul>                                                         |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'between 0 and 1. | BCEWithLogitsLoss'</li></ul>                                                                                    |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'it s possible to trade off recall and precision by adding weights to positive examples. | BCEWithLogitsLoss'</li></ul>             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'in the case of multi label classification the loss can be described as | BCEWithLogitsLoss'</li></ul>                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'ell c x, y l c l 1,c , dots,l n,c ^ top, quad | BCEWithLogitsLoss'</li></ul>                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'l n,c w n,c left p c y n,c cdot log sigma x n,c | BCEWithLogitsLoss'</li></ul>                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'1 y n,c cdot log 1 sigma x n,c right , | BCEWithLogitsLoss'</li></ul>                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for example, if a dataset contains 100 positive and 300 negative examples of a single class, | BCEWithLogitsLoss'</li></ul>        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'then pos weight for the class should be equal to math frac 300 100 3 . | BCEWithLogitsLoss'</li></ul>                              |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'the loss would act as if the dataset contains math 3 times 100 300 positive examples. | BCEWithLogitsLoss'</li></ul>               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'target torch^ones 10, 64 , dtype torch^float32 # 64 classes, batch size 10 | BCEWithLogitsLoss'</li></ul>                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output torch^full 10, 64 , 0999 # a prediction logit | BCEWithLogitsLoss'</li></ul>                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'pos weight torch^ones 64 # all weights are equal to 1 | BCEWithLogitsLoss'</li></ul>                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'criterion torch^nn.bcewithlogitsloss pos weight pos weight | BCEWithLogitsLoss'</li></ul>                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'criterion output, target # log sigmoid 0999 | BCEWithLogitsLoss'</li></ul>                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'tensor 03135 | BCEWithLogitsLoss'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'weight tensor, optional a manual rescaling weight given to the loss | BCEWithLogitsLoss'</li></ul>                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'of each batch element. | BCEWithLogitsLoss'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if given, has to be a tensor of size nbatch . | BCEWithLogitsLoss'</li></ul>                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'size average bool, optional deprecated see attr reduction . | BCEWithLogitsLoss'</li></ul>                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'by default, | BCEWithLogitsLoss'</li></ul>                                                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the losses are averaged over each loss element in the batch. | BCEWithLogitsLoss'</li></ul>                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'note that for | BCEWithLogitsLoss'</li></ul>                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'some losses, there are multiple elements per sample. | BCEWithLogitsLoss'</li></ul>                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if the field attr size average | BCEWithLogitsLoss'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'is set to false , the losses are instead summed for each minibatch. | BCEWithLogitsLoss'</li></ul>                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'ignored | BCEWithLogitsLoss'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'when reduce is false . | BCEWithLogitsLoss'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default true | BCEWithLogitsLoss'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'reduce bool, optional deprecated see attr reduction . | BCEWithLogitsLoss'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'losses are averaged or summed over observations for each minibatch depending | BCEWithLogitsLoss'</li></ul>                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'on attr size average . | BCEWithLogitsLoss'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'when attr reduce is false , returns a loss per | BCEWithLogitsLoss'</li></ul>                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'batch element instead and ignores attr size average . | BCEWithLogitsLoss'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default true | BCEWithLogitsLoss'</li></ul>                                                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'reduction string, optional specifies the reduction to apply to the output | BCEWithLogitsLoss'</li></ul>                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'none mean sum . | BCEWithLogitsLoss'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'none no reduction will be applied, | BCEWithLogitsLoss'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'mean the sum of the output will be divided by the number of | BCEWithLogitsLoss'</li></ul>                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'elements in the output, sum the output will be summed. | BCEWithLogitsLoss'</li></ul>                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'note attr size average | BCEWithLogitsLoss'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'and attr reduce are in the process of being deprecated, and in the meantime, | BCEWithLogitsLoss'</li></ul>                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default mean | BCEWithLogitsLoss'</li></ul>                                                                                        |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'pos weight tensor, optional a weight of positive examples. | BCEWithLogitsLoss'</li></ul>                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'must be a vector with length equal to the number of classes. | BCEWithLogitsLoss'</li></ul>                                        |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'input math n, where math means, any number of additional dimensions | BCEWithLogitsLoss'</li></ul>                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'target math n, , same shape as the input | BCEWithLogitsLoss'</li></ul>                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'output scalar. | BCEWithLogitsLoss'</li></ul>                                                                                      |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'if attr reduction is none , then math n, , same | BCEWithLogitsLoss'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'loss nn^bcewithlogitsloss | BCEWithLogitsLoss'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'input torch^randn 3, requires grad true | BCEWithLogitsLoss'</li></ul>                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'target torch^empty 3 ^random 2 | BCEWithLogitsLoss'</li></ul>                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output loss input, target | BCEWithLogitsLoss'</li></ul>                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output^backward | BCEWithLogitsLoss'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'if attr cmake build type env | BuildType'</li></ul>                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'if cmakecache^txt does not exist, | BuildType'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'arguments | BuildType'</li></ul>                                                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'this class includes all the information needed to benchmark an operator. | Caffe2OperatorTestCase'</li></ul>                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'op bench it s a user defined class child of caffe2benchmarkbase | Caffe2OperatorTestCase'</li></ul>                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'test config a namedtuple includes test name, input shape, tag, run backward. | Caffe2OperatorTestCase'</li></ul>                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'pads the input tensor boundaries with a constant value. | ConstantPad3d'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for n dimensional padding, use func torch^nn.functional^pad . | ConstantPad3d'</li></ul>                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'padding int, tuple the size of the padding. | ConstantPad3d'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'padding in all boundaries. | ConstantPad3d'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'math text padding left , math text padding right , | ConstantPad3d'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m nn^constantpad3d 3, 35 | ConstantPad3d'</li></ul>                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output m input | ConstantPad3d'</li></ul>                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# using different paddings for different sides | ConstantPad3d'</li></ul>                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output m input | ConstantPad3d'</li></ul>                                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'applies a 3d convolution over an input signal composed of several input | Conv3d'</li></ul>                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'planes. | Conv3d'</li></ul>                                                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'and output math n, c out , d out , h out , w out can be precisely described as | Conv3d'</li></ul>                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'out n i, c out j bias c out j | Conv3d'</li></ul>                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'attr stride controls the stride for the cross correlation. | Conv3d'</li></ul>                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'sides for attr padding number of points for each dimension. | Conv3d'</li></ul>                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'it is harder to describe, but this link has a nice visualization of what attr dilation does. | Conv3d'</li></ul>                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'attr in channels and attr out channels must both be divisible by | Conv3d'</li></ul>                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'at groups 1, all inputs are convolved to all outputs. | Conv3d'</li></ul>                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'at groups 2, the operation becomes equivalent to having two conv | Conv3d'</li></ul>                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'layers side by side, each seeing half the input channels, | Conv3d'</li></ul>                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'and producing half the output channels, and both subsequently | Conv3d'</li></ul>                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'concatenated. | Conv3d'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'at groups attr in channels , each input channel is convolved with | Conv3d'</li></ul>                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'its own set of filters, of size | Conv3d'</li></ul>                                                                                |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'math left lfloor frac out channels in channels right rfloor . | Conv3d'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 1]) | <ul><li>'a tuple of three ints in which case, the first int is used for the depth dimension, | Conv3d'</li></ul>                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'in other words, for an input of size math n, c in , d in , h in , w in , | Conv3d'</li></ul>                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'math in channels c in , out channels c in times k, . | Conv3d'</li></ul>                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'in channels int number of channels in the input image | Conv3d'</li></ul>                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'kernel size int or tuple size of the convolving kernel | Conv3d'</li></ul>                                                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'padding int or tuple, optional zero padding added to all three sides of the input. | Conv3d'</li></ul>                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default 0 | Conv3d'</li></ul>                                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'padding mode string, optional . | Conv3d'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'accepted values zeros and circular default zeros | Conv3d'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'dilation int or tuple, optional spacing between kernel elements. | Conv3d'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'groups int, optional number of blocked connections from input channels to output channels. | Conv3d'</li></ul>                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'bias bool, optional if true , adds a learnable bias to the output. | Conv3d'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default true | Conv3d'</li></ul>                                                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'input math n, c in , d in , h in , w in | Conv3d'</li></ul>                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'output math n, c out , d out , h out , w out where | Conv3d'</li></ul>                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'weight tensor the learnable weights of the module of shape | Conv3d'</li></ul>                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the values of these weights are sampled from | Conv3d'</li></ul>                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'math k frac 1 c text in prod i 0 ^ 2 text kernel size i | Conv3d'</li></ul>                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'bias tensor the learnable bias of the module of shape out channels . | Conv3d'</li></ul>                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if attr bias is true , | Conv3d'</li></ul>                                                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'then the values of these weights are | Conv3d'</li></ul>                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'sampled from math mathcal u sqrt k , sqrt k where | Conv3d'</li></ul>                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'math k frac 1 c text in prod i 0 ^ 2 text kernel size i | Conv3d'</li></ul>                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# with square kernels and equal stride | Conv3d'</li></ul>                                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m nn^conv3d 16, 33, 3, stride 2 | Conv3d'</li></ul>                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# non square kernels and unequal stride and with padding | Conv3d'</li></ul>                                                       |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m nn^conv3d 16, 33, 3, 5, 2 , stride 2, 1, 1 , padding 4, 2, 0 | Conv3d'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'input torch^randn 20, 16, 10, 50, 100 | Conv3d'</li></ul>                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output m input | Conv3d'</li></ul>                                                                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a convrelu3d module is a fused module of conv3d and relu | ConvReLU3d'</li></ul>                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the policy cycles the learning | CyclicLR'</li></ul>                                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the paper cyclical learning rates for training neural networks . | CyclicLR'</li></ul>                                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'or per cycle basis. | CyclicLR'</li></ul>                                                                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'cyclical learning rate policy changes the learning rate after every batch. | CyclicLR'</li></ul>                                   |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'triangular2 a basic triangular cycle that scales initial amplitude by half each cycle. | CyclicLR'</li></ul>                       |
| tensor([0, 1, 0, 1, 0]) | <ul><li>'at each cycle iteration. | CyclicLR'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'optimizer torch^optim.sgd model^parameters , lr 01, momentum 09 | CyclicLR'</li></ul>                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'scheduler torch^optim.lr scheduler^cycliclr optimizer, base lr 001, max lr 01 | CyclicLR'</li></ul>                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'data loader torch^utils.data^dataloader . | CyclicLR'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for epoch in range 10 | CyclicLR'</li></ul>                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'for batch in data loader | CyclicLR'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'train batch . | CyclicLR'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'scheduler^step | CyclicLR'</li></ul>                                                                                               |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'this will be swapped as nnq^dequantize in convert . | DeQuantStub'</li></ul>                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a class with torch function and a specific diagonal representation | DiagonalTensor'</li></ul>                                     |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'this class has limited utility and is mostly useful for verifying that the | DiagonalTensor'</li></ul>                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'dispatch mechanism works as expected. | DiagonalTensor'</li></ul>                                                                  |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'it is based on the diagonalarray | DiagonalTensor'</li></ul>                                                                       |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'example in the numpy documentation. | DiagonalTensor'</li></ul>                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'with the pytorch dispatch system happens via the torch function | DiagonalTensor'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'diagonaltensor represents a 2d tensor with n rows and columns that has | DiagonalTensor'</li></ul>                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'diagonal entries set to value and all other entries set to zero. | DiagonalTensor'</li></ul>                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the | DiagonalTensor'</li></ul>                                                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'main functionality of diagonaltensor is to provide a more compact | DiagonalTensor'</li></ul>                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'computes sums or means of bags of embeddings, without instantiating the | EmbeddingBag'</li></ul>                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'intermediate embeddings. | EmbeddingBag'</li></ul>                                                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'for bags of constant length and no attr per sample weights , this class | EmbeddingBag'</li></ul>                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'with mode sum is equivalent to class torch^nn.embedding followed by torch^sum dim 0 , | EmbeddingBag'</li></ul>                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'with mode mean is equivalent to class torch^nn.embedding followed by torch^mean dim 0 , | EmbeddingBag'</li></ul>                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'with mode max is equivalent to class torch^nn.embedding followed by torch^max dim 0 . | EmbeddingBag'</li></ul>                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'however, class torch^nn.embeddingbag is much more time and memory efficient than using a chain of these | EmbeddingBag'</li></ul>  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'operations. | EmbeddingBag'</li></ul>                                                                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'embeddingbag also supports per sample weights as an argument to the forward | EmbeddingBag'</li></ul>                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'pass. | EmbeddingBag'</li></ul>                                                                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this scales the output of the embedding before performing a weighted | EmbeddingBag'</li></ul>                                     |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'reduction as specified by mode . | EmbeddingBag'</li></ul>                                                                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'if attr per sample weights is passed, the | EmbeddingBag'</li></ul>                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'only supported mode is sum , which computes a weighted sum according to | EmbeddingBag'</li></ul>                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'attr per sample weights . | EmbeddingBag'</li></ul>                                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'num embeddings int size of the dictionary of embeddings | EmbeddingBag'</li></ul>                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'embedding dim int the size of each embedding vector | EmbeddingBag'</li></ul>                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'max norm float, optional if given, each embedding vector with norm larger than attr max norm | EmbeddingBag'</li></ul>             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'is renormalized to have norm attr max norm . | EmbeddingBag'</li></ul>                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'norm type float, optional the p of the p norm to compute for the attr max norm option. | EmbeddingBag'</li></ul>                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default 2 . | EmbeddingBag'</li></ul>                                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'scale grad by freq boolean, optional if given, this will scale gradients by the inverse of frequency of | EmbeddingBag'</li></ul>  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the words in the mini batch. | EmbeddingBag'</li></ul>                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default false . | EmbeddingBag'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'mode string, optional sum , mean or max . | EmbeddingBag'</li></ul>                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'specifies the way to reduce the bag. | EmbeddingBag'</li></ul>                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'sum computes the weighted sum, taking attr per sample weights | EmbeddingBag'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'into consideration. | EmbeddingBag'</li></ul>                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'mean computes the average of the values | EmbeddingBag'</li></ul>                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'in the bag, max computes the max value over each bag. | EmbeddingBag'</li></ul>                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default mean | EmbeddingBag'</li></ul>                                                                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'sparse bool, optional if true , gradient w^r.t. attr weight matrix will be a sparse tensor. | EmbeddingBag'</li></ul>              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'notes for more details regarding sparse gradients. | EmbeddingBag'</li></ul>                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'note this option is not | EmbeddingBag'</li></ul>                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'supported when mode max . | EmbeddingBag'</li></ul>                                                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'weight tensor the learnable weights of the module of shape num embeddings, embedding dim | EmbeddingBag'</li></ul>                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'initialized from math mathcal n 0, 1 . | EmbeddingBag'</li></ul>                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'inputs attr input longtensor , attr offsets longtensor, optional , and | EmbeddingBag'</li></ul>                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'attr per index weights tensor, optional | EmbeddingBag'</li></ul>                                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if attr input is 2d of shape b, n , | EmbeddingBag'</li></ul>                                                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'it will be treated as b bags sequences each of fixed length n , and | EmbeddingBag'</li></ul>                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this will return b values aggregated in a way depending on the attr mode . | EmbeddingBag'</li></ul>                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'attr offsets is ignored and required to be none in this case. | EmbeddingBag'</li></ul>                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if attr input is 1d of shape n , | EmbeddingBag'</li></ul>                                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'it will be treated as a concatenation of multiple bags sequences . | EmbeddingBag'</li></ul>                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'attr offsets is required to be a 1d tensor containing the | EmbeddingBag'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'starting index positions of each bag in attr input . | EmbeddingBag'</li></ul>                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'therefore, | EmbeddingBag'</li></ul>                                                                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'for attr offsets of shape b , attr input will be viewed as | EmbeddingBag'</li></ul>                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'having b bags. | EmbeddingBag'</li></ul>                                                                                           |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'empty bags ie, having 0 length will have | EmbeddingBag'</li></ul>                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'returned vectors filled by zeros. | EmbeddingBag'</li></ul>                                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'per sample weights tensor, optional a tensor of float double weights, or none | EmbeddingBag'</li></ul>                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'to indicate all weights should be taken to be 1 . | EmbeddingBag'</li></ul>                                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if specified, attr per sample weights | EmbeddingBag'</li></ul>                                                                    |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'must have exactly the same shape as input and is treated as having the same | EmbeddingBag'</li></ul>                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'attr offsets , if those are not none . | EmbeddingBag'</li></ul>                                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'only supported for mode sum . | EmbeddingBag'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# an embedding module containing 10 tensors of size 3 | EmbeddingBag'</li></ul>                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'embedding sum nn^embeddingbag 10, 3, mode sum | EmbeddingBag'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# a batch of 2 samples of 4 indices each | EmbeddingBag'</li></ul>                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'input torch^longtensor 1,2,4,5,4,3,2,9 | EmbeddingBag'</li></ul>                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'embedding sum input, offsets | EmbeddingBag'</li></ul>                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'11306, 25798, 10044 | EmbeddingBag'</li></ul>                                                                                      |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'raises an error if a key is seen more than once. | EnforceUnique'</li></ul>                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'each error is a section in the output of cuda memcheck. | Error'</li></ul>                                                         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'each error in the report has an error message and a backtrace. | Error'</li></ul>                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'wraps an exception plus traceback to communicate across threads | ExceptionWrapper'</li></ul>                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'executed. | ExternalInitializer'</li></ul>                                                                                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'current version is not doing any real sanity checks to the parameter. | ExternalInitializer'</li></ul>                             |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'creates a fisher snedecor distribution parameterized by attr df1 and attr df2 . | FisherSnedecor'</li></ul>                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m fishersnedecor torch^tensor 10 , torch^tensor 20 | FisherSnedecor'</li></ul>                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'tensor 02453 | FisherSnedecor'</li></ul>                                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'df1 float or tensor degrees of freedom parameter 1 | FisherSnedecor'</li></ul>                                                     |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'collect last n samples from input record. | LastNWindowCollector'</li></ul>                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'if you have complex data, | LastNWindowCollector'</li></ul>                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'use packrecords to pack it before using this layer. | LastNWindowCollector'</li></ul>                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this layer is not thread safe. | LastNWindowCollector'</li></ul>                                                                   |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'implements l bfgs algorithm, heavily inspired by minfunc | LBFGS'</li></ul>                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'this is a very memory intensive optimizer it requires additional | LBFGS'</li></ul>                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'param bytes history size 1 bytes . | LBFGS'</li></ul>                                                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'if it doesn t fit in memory | LBFGS'</li></ul>                                                                                     |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'try reducing the history size, or use a different algorithm. | LBFGS'</li></ul>                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'arguments | LBFGS'</li></ul>                                                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'max iter int maximal number of iterations per optimization step | LBFGS'</li></ul>                                                 |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'max eval int maximal number of function evaluations per optimization | LBFGS'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default 1e 5 . | LBFGS'</li></ul>                                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'value parameter changes default 1e 9 . | LBFGS'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'line search fn str either strong wolfe or none default none . | LBFGS'</li></ul>                                                   |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'modules can also contain other modules, allowing to nest them in | Module'</li></ul>                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'a tree structure. | Module'</li></ul>                                                                                              |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'you can assign the submodules as regular attributes | Module'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'import torch^nn.functional as f | Module'</li></ul>                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'def init self | Module'</li></ul>                                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'super model, self . | Module'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'init | Module'</li></ul>                                                                                                           |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'self^conv1 nn^conv2d 1, 20, 5 | Module'</li></ul>                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'self^conv2 nn^conv2d 20, 20, 5 | Module'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'def forward self, x | Module'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'x f^relu self^conv1 x | Module'</li></ul>                                                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'return f^relu self^conv2 x | Module'</li></ul>                                                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'submodules assigned in this way will be registered, and will have their | Module'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'parameters converted too when you call meth to , etc | Module'</li></ul>                                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'creates a criterion that optimizes a multi class multi classification | MultiLabelMarginLoss'</li></ul>                            |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'hinge loss margin based loss between input math x a 2d mini batch tensor | MultiLabelMarginLoss'</li></ul>                         |
| tensor([0, 0, 0, 1, 1]) | <ul><li>'and output math y which is a 2d tensor of target class indices . | MultiLabelMarginLoss'</li></ul>                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'for each sample in the mini batch | MultiLabelMarginLoss'</li></ul>                                                                |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'text loss x, y sum ij frac max 0, 1 x y j x i text x^size 0 | MultiLabelMarginLoss'</li></ul>                                      |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'the criterion only considers a contiguous block of non negative targets that | MultiLabelMarginLoss'</li></ul>                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'starts at the front. | MultiLabelMarginLoss'</li></ul>                                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this allows for different samples to have variable amounts of target classes. | MultiLabelMarginLoss'</li></ul>                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'size average bool, optional deprecated see attr reduction . | MultiLabelMarginLoss'</li></ul>                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'by default, | MultiLabelMarginLoss'</li></ul>                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the losses are averaged over each loss element in the batch. | MultiLabelMarginLoss'</li></ul>                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'note that for | MultiLabelMarginLoss'</li></ul>                                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'some losses, there are multiple elements per sample. | MultiLabelMarginLoss'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'if the field attr size average | MultiLabelMarginLoss'</li></ul>                                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'is set to false , the losses are instead summed for each minibatch. | MultiLabelMarginLoss'</li></ul>                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'ignored | MultiLabelMarginLoss'</li></ul>                                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'when reduce is false . | MultiLabelMarginLoss'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default true | MultiLabelMarginLoss'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'reduce bool, optional deprecated see attr reduction . | MultiLabelMarginLoss'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'losses are averaged or summed over observations for each minibatch depending | MultiLabelMarginLoss'</li></ul>                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'on attr size average . | MultiLabelMarginLoss'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'when attr reduce is false , returns a loss per | MultiLabelMarginLoss'</li></ul>                                                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'batch element instead and ignores attr size average . | MultiLabelMarginLoss'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default true | MultiLabelMarginLoss'</li></ul>                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'reduction string, optional specifies the reduction to apply to the output | MultiLabelMarginLoss'</li></ul>                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'none mean sum . | MultiLabelMarginLoss'</li></ul>                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'none no reduction will be applied, | MultiLabelMarginLoss'</li></ul>                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'mean the sum of the output will be divided by the number of | MultiLabelMarginLoss'</li></ul>                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'elements in the output, sum the output will be summed. | MultiLabelMarginLoss'</li></ul>                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'note attr size average | MultiLabelMarginLoss'</li></ul>                                                                           |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'and attr reduce are in the process of being deprecated, and in the meantime, | MultiLabelMarginLoss'</li></ul>                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default mean | MultiLabelMarginLoss'</li></ul>                                                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'input math c or math n, c where n is the batch size and c | MultiLabelMarginLoss'</li></ul>                                        |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'target math c or math n, c , label targets padded by 1 ensuring same shape as the input. | MultiLabelMarginLoss'</li></ul>         |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'if attr reduction is none , then math n . | MultiLabelMarginLoss'</li></ul>                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'loss nn^multilabelmarginloss | MultiLabelMarginLoss'</li></ul>                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'x torch^floattensor 01, 02, 04, 08 | MultiLabelMarginLoss'</li></ul>                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# for target y, only consider labels 3 and 0, not after label 1 | MultiLabelMarginLoss'</li></ul>                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'y torch^longtensor 3, 0, 1, 1 | MultiLabelMarginLoss'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'loss x, y | MultiLabelMarginLoss'</li></ul>                                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# 025 1 01 02 1 01 04 1 08 02 1 08 04 | MultiLabelMarginLoss'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'tensor 08500 | MultiLabelMarginLoss'</li></ul>                                                                                     |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'inherited classes should implement the modify net method where | NetModifier'</li></ul>                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'example usage | NetModifier'</li></ul>                                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'modifier somenetmodifier opts | NetModifier'</li></ul>                                                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'modifier net | NetModifier'</li></ul>                                                                                              |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'creates a one hot categorical distribution parameterized by attr probs or | OneHotCategorical'</li></ul>                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'attr logits . | OneHotCategorical'</li></ul>                                                                                       |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'samples are one hot coded vectors of size probs^size 1 . | OneHotCategorical'</li></ul>                                            |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'attr probs and attr logits . | OneHotCategorical'</li></ul>                                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m onehotcategorical torch^tensor 025, 025, 025, 025 | OneHotCategorical'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m^sample # equal probability of 0, 1, 2, 3 | OneHotCategorical'</li></ul>                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'tensor 0., 0., 0., 1. | OneHotCategorical'</li></ul>                                                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'probs tensor event probabilities | OneHotCategorical'</li></ul>                                                                    |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'logits tensor event log probabilities | OneHotCategorical'</li></ul>                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'creates a poisson distribution parameterized by attr rate , the rate parameter. | Poisson'</li></ul>                               |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'samples are nonnegative integers, with a pmf given by | Poisson'</li></ul>                                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m poisson torch^tensor 4 | Poisson'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'m^sample | Poisson'</li></ul>                                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'tensor 3. | Poisson'</li></ul>                                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'rate number, tensor the rate parameter | Poisson'</li></ul>                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a wrapper class that wraps the input module, adds quantstub and | QuantWrapper'</li></ul>                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'dequantstub and surround the call to module with call to quant and dequant | QuantWrapper'</li></ul>                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'modules. | QuantWrapper'</li></ul>                                                                                                 |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'this is used by the quantization utility functions to add the quant and | QuantWrapper'</li></ul>                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'dequant modules, before convert function quantstub will just be observer, | QuantWrapper'</li></ul>                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'it observes the input tensor, after convert , quantstub | QuantWrapper'</li></ul>                                                  |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'will be swapped to nnq^quantize which does actual quantization. | QuantWrapper'</li></ul>                                          |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'similarly | QuantWrapper'</li></ul>                                                                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'for dequantstub . | QuantWrapper'</li></ul>                                                                                        |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'implements stochastic gradient descent optionally with momentum . | SGD'</li></ul>                                                 |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'nesterov momentum is based on the formula from | SGD'</li></ul>                                                                    |
| tensor([0, 0, 1, 1, 0]) | <ul><li>'on the importance of initialization and momentum in deep learning . | SGD'</li></ul>                                               |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'lr float learning rate | SGD'</li></ul>                                                                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'momentum float, optional momentum factor default 0 | SGD'</li></ul>                                                                |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'dampening float, optional dampening for momentum default 0 | SGD'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'nesterov bool, optional enables nesterov momentum default false | SGD'</li></ul>                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'optimizer torch^optim.sgd model^parameters , lr 01, momentum 09 | SGD'</li></ul>                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'optimizer^zero grad | SGD'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'loss fn model input , target ^backward | SGD'</li></ul>                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'optimizer^step | SGD'</li></ul>                                                                                                    |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'dictionary from multiprocessing handles to storageweakref | SharedCache'</li></ul>                                                 |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'transform functor that applies a sequence of transforms tseq | StackTransform'</li></ul>                                           |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'in a way compatible with func torch^stack . | StackTransform'</li></ul>                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'x torch^stack torch^range 1, 10 , torch^range 1, 10 , dim 1 | StackTransform'</li></ul>                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'t stacktransform exptransform , identity transform , dim 1 | StackTransform'</li></ul>                                             |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'y t x | StackTransform'</li></ul>                                                                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'subset of a dataset at specified indices. | Subset'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'arguments | Subset'</li></ul>                                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'dataset dataset the whole dataset | Subset'</li></ul>                                                                              |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'indices sequence indices in the whole set selected for subset | Subset'</li></ul>                                                  |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'a task is composed of an execution step and zero or more outputs. | Task'</li></ul>                                                |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'tasks are executed in the context of a taskgroup, which, in turn, can | Task'</li></ul>                                            |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'be run by a session. | Task'</li></ul>                                                                                             |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'task outputs are fetched by the session at the end of the run. | Task'</li></ul>                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'from net builder import ops | Task'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with node trainer , task name my task , num instances 2 | Task'</li></ul>                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with ops^task init | Task'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'globl ops^const 0 | Task'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with ops^task instance init | Task'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'local ops^const 0 | Task'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with ops^loop 100 | Task'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'ops^copy globl, local | Task'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with ops^task instance exit | Task'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'ops^add globl, local , globl | Task'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with ops^task exit | Task'</li></ul>                                                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'ops^mul globl, globl , globl | Task'</li></ul>                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the task above will create 2 instances that will run in parallel. | Task'</li></ul>                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'each instance will copy local to globl 100 times, then add local | Task'</li></ul>                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'to globl once. | Task'</li></ul>                                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'the mul will only execute once, after all the instances | Task'</li></ul>                                                          |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'of the task have finished. | Task'</li></ul>                                                                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'represents the output of a task. | TaskOutput'</li></ul>                                                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'ashish vaswani, noam shazeer, niki parmar, jakob uszkoreit, llion jones, aidan n gomez, | TransformerEncoderLayer'</li></ul>       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'lukasz kaiser, and illia polosukhin. | TransformerEncoderLayer'</li></ul>                                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'2017 | TransformerEncoderLayer'</li></ul>                                                                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'attention is all you need. | TransformerEncoderLayer'</li></ul>                                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'in advances in | TransformerEncoderLayer'</li></ul>                                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'neural information processing systems, pages 6000 6010. | TransformerEncoderLayer'</li></ul>                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'users may modify or implement | TransformerEncoderLayer'</li></ul>                                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'in a different way during application. | TransformerEncoderLayer'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'nhead the number of heads in the multiheadattention models required . | TransformerEncoderLayer'</li></ul>                         |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'dropout the dropout value default 01 . | TransformerEncoderLayer'</li></ul>                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'encoder layer nn^transformerencoderlayer d model 512, nhead 8 | TransformerEncoderLayer'</li></ul>                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'out encoder layer src | TransformerEncoderLayer'</li></ul>                                                                         |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'where math n is the batch dimension, math c is the channel dimension, | Unfold'</li></ul>                                          |
| tensor([1, 1, 0, 0, 0]) | <ul><li>'and math represent arbitrary spatial dimensions. | Unfold'</li></ul>                                                               |
| tensor([0, 0, 0, 1, 0]) | <ul><li>'of attr input math above , and math d is over all spatial | Unfold'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'therefore, indexing attr output at the last dimension column dimension | Unfold'</li></ul>                                         |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'gives all values within a certain block. | Unfold'</li></ul>                                                                       |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'the attr padding , attr stride and attr dilation arguments specify | Unfold'</li></ul>                                             |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'how the sliding blocks are retrieved. | Unfold'</li></ul>                                                                          |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'reshaping. | Unfold'</li></ul>                                                                                                     |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'it is harder to describe, but this link has a nice visualization of what attr dilation does. | Unfold'</li></ul>                   |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'kernel size int or tuple the size of the sliding blocks | Unfold'</li></ul>                                                        |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'padding int or tuple, optional implicit zero padding to be added on | Unfold'</li></ul>                                            |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'default 0 | Unfold'</li></ul>                                                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'stride of elements within the | Unfold'</li></ul>                                                                                  |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'attr stride is an int or a tuple of length 1, their values will be | Unfold'</li></ul>                                             |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'replicated across all spatial dimensions. | Unfold'</li></ul>                                                                      |
| tensor([0, 1, 0, 0, 0]) | <ul><li>'called im2col . | Unfold'</li></ul>                                                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'class torch^nn.fold calculates each combined value in the resulting | Unfold'</li></ul>                                            |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'large tensor by summing all values from all containing blocks. | Unfold'</li></ul>                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'class torch^nn.unfold extracts the values in the local blocks by | Unfold'</li></ul>                                               |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'copying from the large tensor. | Unfold'</li></ul>                                                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'so, if the blocks overlap, they are not | Unfold'</li></ul>                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'inverses of each other. | Unfold'</li></ul>                                                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'in general, folding and unfolding operations are related as | Unfold'</li></ul>                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'follows. | Unfold'</li></ul>                                                                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'consider class torch^nn.fold and | Unfold'</li></ul>                                                                               |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'class torch^nn.unfold instances created with the same | Unfold'</li></ul>                                                          |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'fold params dict kernel size . | Unfold'</li></ul>                                                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>', dilation . | Unfold'</li></ul>                                                                                                   |
| tensor([0, 0, 1, 0, 0]) | <ul><li>', padding . | Unfold'</li></ul>                                                                                                    |
| tensor([0, 0, 1, 0, 0]) | <ul><li>', stride . | Unfold'</li></ul>                                                                                                     |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'fold nn^fold output size . | Unfold'</li></ul>                                                                                     |
| tensor([0, 0, 1, 0, 0]) | <ul><li>', fold params | Unfold'</li></ul>                                                                                                  |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'unfold nn^unfold fold params | Unfold'</li></ul>                                                                                   |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'then for any supported input tensor the following | Unfold'</li></ul>                                                              |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'equality holds | Unfold'</li></ul>                                                                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'fold unfold input divisor input | Unfold'</li></ul>                                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'where divisor is a tensor that depends only on the shape | Unfold'</li></ul>                                                       |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'and dtype of the input | Unfold'</li></ul>                                                                                         |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'input ones torch^ones input^shape, dtype input^dtype | Unfold'</li></ul>                                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'divisor fold unfold input ones | Unfold'</li></ul>                                                                                 |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'when the divisor tensor contains no zero elements, then | Unfold'</li></ul>                                                        |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'fold and unfold operations are inverses of each | Unfold'</li></ul>                                                                |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'other up to constant divisor . | Unfold'</li></ul>                                                                                 |
| tensor([1, 0, 0, 1, 0]) | <ul><li>'output math n, c times prod text kernel size , l as described above | Unfold'</li></ul>                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'unfold nn^unfold kernel size 2, 3 | Unfold'</li></ul>                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'output unfold input | Unfold'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# 4 blocks 2x3 kernels in total in the 3x4 input | Unfold'</li></ul>                                                               |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'torch^size 2, 30, 4 | Unfold'</li></ul>                                                                                            |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'inp torch^randn 1, 3, 10, 12 | Unfold'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'inp unf torch^nn.functional^unfold inp, 4, 5 | Unfold'</li></ul>                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'out torch^nn.functional^fold out unf, 7, 8 , 1, 1 | Unfold'</li></ul>                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'# out out unf^view 1, 2, 7, 8 | Unfold'</li></ul>                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'tensor 19073e 06 | Unfold'</li></ul>                                                                                               |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'context class to allow setting the current context. | UseOptimizer'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'example usage with brew | UseOptimizer'</li></ul>                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with useoptimizer optim | UseOptimizer'</li></ul>                                                                                  |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'brew^func | UseOptimizer'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with useoptimizer weight weight optim | UseOptimizer'</li></ul>                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'brew^func | UseOptimizer'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with useoptimizer default optim, bias bias optim, | UseOptimizer'</li></ul>                                                        |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'weight weight optim | UseOptimizer'</li></ul>                                                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'brew^func | UseOptimizer'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'brew^func | UseOptimizer'</li></ul>                                                                                                |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'with useoptimizer optim2 | UseOptimizer'</li></ul>                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'brew^func | UseOptimizer'</li></ul>                                                                                                |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'base class that all auth implementations derive from | AuthBase'</li></ul>                                                         |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the fully mutable class preparedrequest preparedrequest object, | PreparedRequest'</li></ul>                                       |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'containing the exact bytes that will be sent to the server. | PreparedRequest'</li></ul>                                           |
| tensor([0, 0, 1, 0, 0]) | <ul><li>'generated from either a class request request object or manually. | PreparedRequest'</li></ul>                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'usage | PreparedRequest'</li></ul>                                                                                                 |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'req requests^request get , https httpbin^org get | PreparedRequest'</li></ul>                                                      |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'r | PreparedRequest'</li></ul>                                                                                                     |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'preparedrequest get | PreparedRequest'</li></ul>                                                                                   |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'s requests^session | PreparedRequest'</li></ul>                                                                                    |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'s^send r | PreparedRequest'</li></ul>                                                                                              |
| tensor([1, 0, 0, 0, 0]) | <ul><li>'response 200 | PreparedRequest'</li></ul>                                                                                          |
| tensor([0, 0, 0, 0, 1]) | <ul><li>'the class response response object, which contains a | Response'</li></ul>                                                         |

## Uses

### Direct Use for Inference

First install the SetFit library:

```bash
pip install setfit
```

Then you can load this model and run inference.

```python
from setfit import SetFitModel

# Download from the 🤗 Hub
model = SetFitModel.from_pretrained("setfit_model_id")
# Run inference
preds = model("sep suppress | SkipTo")
```

<!--
### Downstream Use

*List how someone could finetune this model on their own dataset.*
-->

<!--
### Out-of-Scope Use

*List how the model may foreseeably be misused and address what users ought not to do with the model.*
-->

<!--
## Bias, Risks and Limitations

*What are the known or foreseeable issues stemming from this model? You could also flag here known failure cases or weaknesses of the model.*
-->

<!--
### Recommendations

*What are recommendations with respect to the foreseeable issues? For example, filtering explicit content.*
-->

## Training Details

### Training Set Metrics
| Training set | Min       | Median         | Max        |
|:-------------|:----------|:---------------|:-----------|
| Word count   | tensor(3) | tensor(8.9655) | tensor(28) |

### Training Hyperparameters
- batch_size: (32, 32)
- num_epochs: (5, 5)
- max_steps: -1
- sampling_strategy: oversampling
- num_iterations: 20
- body_learning_rate: (2e-05, 2e-05)
- head_learning_rate: 2e-05
- loss: CosineSimilarityLoss
- distance_metric: cosine_distance
- margin: 0.25
- end_to_end: False
- use_amp: False
- warmup_proportion: 0.1
- l2_weight: 0.01
- seed: 42
- eval_max_steps: -1
- load_best_model_at_end: False

### Training Results
| Epoch  | Step  | Training Loss | Validation Loss |
|:------:|:-----:|:-------------:|:---------------:|
| 0.0004 | 1     | 0.2599        | -               |
| 0.0212 | 50    | 0.2605        | -               |
| 0.0425 | 100   | 0.2712        | -               |
| 0.0637 | 150   | 0.266         | -               |
| 0.0849 | 200   | 0.2584        | -               |
| 0.1062 | 250   | 0.2496        | -               |
| 0.1274 | 300   | 0.2541        | -               |
| 0.1486 | 350   | 0.2525        | -               |
| 0.1699 | 400   | 0.2504        | -               |
| 0.1911 | 450   | 0.2486        | -               |
| 0.2123 | 500   | 0.2464        | -               |
| 0.2335 | 550   | 0.2485        | -               |
| 0.2548 | 600   | 0.2451        | -               |
| 0.2760 | 650   | 0.2428        | -               |
| 0.2972 | 700   | 0.2408        | -               |
| 0.3185 | 750   | 0.242         | -               |
| 0.3397 | 800   | 0.2356        | -               |
| 0.3609 | 850   | 0.2356        | -               |
| 0.3822 | 900   | 0.2325        | -               |
| 0.4034 | 950   | 0.2289        | -               |
| 0.4246 | 1000  | 0.218         | -               |
| 0.4459 | 1050  | 0.2151        | -               |
| 0.4671 | 1100  | 0.2006        | -               |
| 0.4883 | 1150  | 0.1929        | -               |
| 0.5096 | 1200  | 0.1864        | -               |
| 0.5308 | 1250  | 0.1872        | -               |
| 0.5520 | 1300  | 0.172         | -               |
| 0.5732 | 1350  | 0.1595        | -               |
| 0.5945 | 1400  | 0.16          | -               |
| 0.6157 | 1450  | 0.1577        | -               |
| 0.6369 | 1500  | 0.1557        | -               |
| 0.6582 | 1550  | 0.1429        | -               |
| 0.6794 | 1600  | 0.1446        | -               |
| 0.7006 | 1650  | 0.1445        | -               |
| 0.7219 | 1700  | 0.1264        | -               |
| 0.7431 | 1750  | 0.1214        | -               |
| 0.7643 | 1800  | 0.126         | -               |
| 0.7856 | 1850  | 0.1192        | -               |
| 0.8068 | 1900  | 0.1148        | -               |
| 0.8280 | 1950  | 0.1153        | -               |
| 0.8493 | 2000  | 0.1106        | -               |
| 0.8705 | 2050  | 0.1098        | -               |
| 0.8917 | 2100  | 0.1085        | -               |
| 0.9130 | 2150  | 0.1102        | -               |
| 0.9342 | 2200  | 0.1025        | -               |
| 0.9554 | 2250  | 0.1009        | -               |
| 0.9766 | 2300  | 0.0978        | -               |
| 0.9979 | 2350  | 0.0935        | -               |
| 1.0191 | 2400  | 0.0883        | -               |
| 1.0403 | 2450  | 0.0894        | -               |
| 1.0616 | 2500  | 0.0842        | -               |
| 1.0828 | 2550  | 0.0892        | -               |
| 1.1040 | 2600  | 0.0833        | -               |
| 1.1253 | 2650  | 0.0871        | -               |
| 1.1465 | 2700  | 0.0873        | -               |
| 1.1677 | 2750  | 0.0877        | -               |
| 1.1890 | 2800  | 0.0822        | -               |
| 1.2102 | 2850  | 0.0805        | -               |
| 1.2314 | 2900  | 0.0731        | -               |
| 1.2527 | 2950  | 0.0776        | -               |
| 1.2739 | 3000  | 0.0739        | -               |
| 1.2951 | 3050  | 0.079         | -               |
| 1.3163 | 3100  | 0.0722        | -               |
| 1.3376 | 3150  | 0.0776        | -               |
| 1.3588 | 3200  | 0.0748        | -               |
| 1.3800 | 3250  | 0.0714        | -               |
| 1.4013 | 3300  | 0.0727        | -               |
| 1.4225 | 3350  | 0.0704        | -               |
| 1.4437 | 3400  | 0.0672        | -               |
| 1.4650 | 3450  | 0.0692        | -               |
| 1.4862 | 3500  | 0.0719        | -               |
| 1.5074 | 3550  | 0.0654        | -               |
| 1.5287 | 3600  | 0.0635        | -               |
| 1.5499 | 3650  | 0.0677        | -               |
| 1.5711 | 3700  | 0.0564        | -               |
| 1.5924 | 3750  | 0.064         | -               |
| 1.6136 | 3800  | 0.0614        | -               |
| 1.6348 | 3850  | 0.0595        | -               |
| 1.6561 | 3900  | 0.0619        | -               |
| 1.6773 | 3950  | 0.0606        | -               |
| 1.6985 | 4000  | 0.0559        | -               |
| 1.7197 | 4050  | 0.0554        | -               |
| 1.7410 | 4100  | 0.0593        | -               |
| 1.7622 | 4150  | 0.053         | -               |
| 1.7834 | 4200  | 0.0602        | -               |
| 1.8047 | 4250  | 0.0591        | -               |
| 1.8259 | 4300  | 0.0549        | -               |
| 1.8471 | 4350  | 0.0536        | -               |
| 1.8684 | 4400  | 0.0561        | -               |
| 1.8896 | 4450  | 0.0547        | -               |
| 1.9108 | 4500  | 0.0538        | -               |
| 1.9321 | 4550  | 0.0552        | -               |
| 1.9533 | 4600  | 0.0462        | -               |
| 1.9745 | 4650  | 0.0431        | -               |
| 1.9958 | 4700  | 0.0506        | -               |
| 2.0170 | 4750  | 0.0486        | -               |
| 2.0382 | 4800  | 0.0448        | -               |
| 2.0594 | 4850  | 0.047         | -               |
| 2.0807 | 4900  | 0.0428        | -               |
| 2.1019 | 4950  | 0.0443        | -               |
| 2.1231 | 5000  | 0.0443        | -               |
| 2.1444 | 5050  | 0.0427        | -               |
| 2.1656 | 5100  | 0.0458        | -               |
| 2.1868 | 5150  | 0.0422        | -               |
| 2.2081 | 5200  | 0.0444        | -               |
| 2.2293 | 5250  | 0.0416        | -               |
| 2.2505 | 5300  | 0.0442        | -               |
| 2.2718 | 5350  | 0.0391        | -               |
| 2.2930 | 5400  | 0.0449        | -               |
| 2.3142 | 5450  | 0.041         | -               |
| 2.3355 | 5500  | 0.0396        | -               |
| 2.3567 | 5550  | 0.0363        | -               |
| 2.3779 | 5600  | 0.0438        | -               |
| 2.3992 | 5650  | 0.0395        | -               |
| 2.4204 | 5700  | 0.0377        | -               |
| 2.4416 | 5750  | 0.0389        | -               |
| 2.4628 | 5800  | 0.0374        | -               |
| 2.4841 | 5850  | 0.0366        | -               |
| 2.5053 | 5900  | 0.0375        | -               |
| 2.5265 | 5950  | 0.04          | -               |
| 2.5478 | 6000  | 0.0377        | -               |
| 2.5690 | 6050  | 0.0382        | -               |
| 2.5902 | 6100  | 0.0319        | -               |
| 2.6115 | 6150  | 0.0361        | -               |
| 2.6327 | 6200  | 0.0341        | -               |
| 2.6539 | 6250  | 0.0317        | -               |
| 2.6752 | 6300  | 0.0334        | -               |
| 2.6964 | 6350  | 0.034         | -               |
| 2.7176 | 6400  | 0.033         | -               |
| 2.7389 | 6450  | 0.0365        | -               |
| 2.7601 | 6500  | 0.0345        | -               |
| 2.7813 | 6550  | 0.0279        | -               |
| 2.8025 | 6600  | 0.0331        | -               |
| 2.8238 | 6650  | 0.0323        | -               |
| 2.8450 | 6700  | 0.032         | -               |
| 2.8662 | 6750  | 0.0304        | -               |
| 2.8875 | 6800  | 0.0343        | -               |
| 2.9087 | 6850  | 0.0326        | -               |
| 2.9299 | 6900  | 0.0339        | -               |
| 2.9512 | 6950  | 0.0286        | -               |
| 2.9724 | 7000  | 0.0312        | -               |
| 2.9936 | 7050  | 0.0263        | -               |
| 3.0149 | 7100  | 0.0268        | -               |
| 3.0361 | 7150  | 0.0293        | -               |
| 3.0573 | 7200  | 0.0239        | -               |
| 3.0786 | 7250  | 0.0333        | -               |
| 3.0998 | 7300  | 0.0257        | -               |
| 3.1210 | 7350  | 0.029         | -               |
| 3.1423 | 7400  | 0.0299        | -               |
| 3.1635 | 7450  | 0.0297        | -               |
| 3.1847 | 7500  | 0.0262        | -               |
| 3.2059 | 7550  | 0.0248        | -               |
| 3.2272 | 7600  | 0.0276        | -               |
| 3.2484 | 7650  | 0.0317        | -               |
| 3.2696 | 7700  | 0.0284        | -               |
| 3.2909 | 7750  | 0.0308        | -               |
| 3.3121 | 7800  | 0.0258        | -               |
| 3.3333 | 7850  | 0.0298        | -               |
| 3.3546 | 7900  | 0.0292        | -               |
| 3.3758 | 7950  | 0.026         | -               |
| 3.3970 | 8000  | 0.0267        | -               |
| 3.4183 | 8050  | 0.0252        | -               |
| 3.4395 | 8100  | 0.0309        | -               |
| 3.4607 | 8150  | 0.027         | -               |
| 3.4820 | 8200  | 0.0238        | -               |
| 3.5032 | 8250  | 0.0257        | -               |
| 3.5244 | 8300  | 0.0265        | -               |
| 3.5456 | 8350  | 0.0275        | -               |
| 3.5669 | 8400  | 0.0235        | -               |
| 3.5881 | 8450  | 0.0273        | -               |
| 3.6093 | 8500  | 0.0293        | -               |
| 3.6306 | 8550  | 0.0279        | -               |
| 3.6518 | 8600  | 0.0237        | -               |
| 3.6730 | 8650  | 0.0226        | -               |
| 3.6943 | 8700  | 0.0237        | -               |
| 3.7155 | 8750  | 0.0305        | -               |
| 3.7367 | 8800  | 0.0263        | -               |
| 3.7580 | 8850  | 0.0252        | -               |
| 3.7792 | 8900  | 0.025         | -               |
| 3.8004 | 8950  | 0.0313        | -               |
| 3.8217 | 9000  | 0.0255        | -               |
| 3.8429 | 9050  | 0.0249        | -               |
| 3.8641 | 9100  | 0.0251        | -               |
| 3.8854 | 9150  | 0.0236        | -               |
| 3.9066 | 9200  | 0.0249        | -               |
| 3.9278 | 9250  | 0.0237        | -               |
| 3.9490 | 9300  | 0.0253        | -               |
| 3.9703 | 9350  | 0.0242        | -               |
| 3.9915 | 9400  | 0.0262        | -               |
| 4.0127 | 9450  | 0.0257        | -               |
| 4.0340 | 9500  | 0.0238        | -               |
| 4.0552 | 9550  | 0.0257        | -               |
| 4.0764 | 9600  | 0.0269        | -               |
| 4.0977 | 9650  | 0.0245        | -               |
| 4.1189 | 9700  | 0.0249        | -               |
| 4.1401 | 9750  | 0.0247        | -               |
| 4.1614 | 9800  | 0.0224        | -               |
| 4.1826 | 9850  | 0.0227        | -               |
| 4.2038 | 9900  | 0.0228        | -               |
| 4.2251 | 9950  | 0.0227        | -               |
| 4.2463 | 10000 | 0.0255        | -               |
| 4.2675 | 10050 | 0.0226        | -               |
| 4.2887 | 10100 | 0.0223        | -               |
| 4.3100 | 10150 | 0.0246        | -               |
| 4.3312 | 10200 | 0.022         | -               |
| 4.3524 | 10250 | 0.021         | -               |
| 4.3737 | 10300 | 0.021         | -               |
| 4.3949 | 10350 | 0.0229        | -               |
| 4.4161 | 10400 | 0.0226        | -               |
| 4.4374 | 10450 | 0.0249        | -               |
| 4.4586 | 10500 | 0.026         | -               |
| 4.4798 | 10550 | 0.0227        | -               |
| 4.5011 | 10600 | 0.0251        | -               |
| 4.5223 | 10650 | 0.0226        | -               |
| 4.5435 | 10700 | 0.0237        | -               |
| 4.5648 | 10750 | 0.0218        | -               |
| 4.5860 | 10800 | 0.024         | -               |
| 4.6072 | 10850 | 0.0245        | -               |
| 4.6285 | 10900 | 0.0247        | -               |
| 4.6497 | 10950 | 0.0228        | -               |
| 4.6709 | 11000 | 0.0182        | -               |
| 4.6921 | 11050 | 0.0226        | -               |
| 4.7134 | 11100 | 0.0201        | -               |
| 4.7346 | 11150 | 0.0231        | -               |
| 4.7558 | 11200 | 0.0201        | -               |
| 4.7771 | 11250 | 0.0245        | -               |
| 4.7983 | 11300 | 0.0217        | -               |
| 4.8195 | 11350 | 0.0232        | -               |
| 4.8408 | 11400 | 0.0221        | -               |
| 4.8620 | 11450 | 0.0244        | -               |
| 4.8832 | 11500 | 0.0235        | -               |
| 4.9045 | 11550 | 0.024         | -               |
| 4.9257 | 11600 | 0.0237        | -               |
| 4.9469 | 11650 | 0.0213        | -               |
| 4.9682 | 11700 | 0.0226        | -               |
| 4.9894 | 11750 | 0.0249        | -               |

### Framework Versions
- Python: 3.11.9
- SetFit: 1.1.0
- Sentence Transformers: 3.3.0
- Transformers: 4.45.2
- PyTorch: 2.5.1+cu118
- Datasets: 3.1.0
- Tokenizers: 0.20.3

## Citation

### BibTeX
```bibtex
@article{https://doi.org/10.48550/arxiv.2209.11055,
    doi = {10.48550/ARXIV.2209.11055},
    url = {https://arxiv.org/abs/2209.11055},
    author = {Tunstall, Lewis and Reimers, Nils and Jo, Unso Eun Seo and Bates, Luke and Korat, Daniel and Wasserblat, Moshe and Pereg, Oren},
    keywords = {Computation and Language (cs.CL), FOS: Computer and information sciences, FOS: Computer and information sciences},
    title = {Efficient Few-Shot Learning Without Prompts},
    publisher = {arXiv},
    year = {2022},
    copyright = {Creative Commons Attribution 4.0 International}
}
```

<!--
## Glossary

*Clearly define terms in order to be accessible across audiences.*
-->

<!--
## Model Card Authors

*Lists the people who create the model card, providing recognition and accountability for the detailed work that goes into its construction.*
-->

<!--
## Model Card Contact

*Provides a way for people who have updates to the Model Card, suggestions, or questions, to contact the Model Card authors.*
-->