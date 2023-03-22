# DictionaryApp
### Its a Dictionary App which Implements Clean Architecture developed in JetPack Compose










# Tech stack & Open-source libraries

* Minimum SDK level 24

* Kotlin based, Coroutines + Flow for asynchronous.

* Jetpack Compose and Dependencies :

    * Lifecycle: Observe Android lifecycles and handle UI states upon the lifecycle changes.
    * ViewModel: Manages UI-related data holder and lifecycle aware. Allows data to survive configuration changes such as screen rotations.
    * Dagger-Hilt: for dependency injection.
    * Retrofit: for retreiving data from the api (https://dictionaryapi.dev).
    * Room-Database: for Local catching (means that if there is no network for the api call we can still fetch the data we previously searched using the room database) the data fetched from the api.
      * Here Room is acting a single source of truth.
* Architecture :

    * Clean Architecture (Ui or Presentation - Domain - Data).
