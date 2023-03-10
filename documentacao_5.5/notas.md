|11 titulos
|----71 sub
|--------380 subsub
|------------489 subsubsub

# Prólogo
	- Notas de versão
	- Guia de atualização
	- Guia de contribuição
	- Documentação da API

# Começando
	- Instalação
		- Server Requirements
		- Installing Laravel
		- Configuration
		- Web Server Configuration
			- Pretty URLs

	- Configuração
		- Introduction
		- Environment Configuration
			- Retrieving Environment Configuration
			- Determining The Current Environment
		- Accessing Configuration Values
		- Configuration Caching
		- Maintenance Mode

	- Estrutura de Diretórios
		- Introduction
		- The Root Directory
			- The app Directory
			- The bootstrap Directory
			- The config Directory
			- The database Directory
			- The public Directory
			- The resources Directory
			- The routes Directory
			- The storage Directory
			- The tests Directory
			- The vendor Directory
		- The App Directory
			- The Console Directory
			- The Events Directory
			- The Exceptions Directory
			- The Http Directory
			- The Jobs Directory
			- The Listeners Directory
			- The Mail Directory
			- The Notifications Directory
			- The Policies Directory
			- The Providers Directory
			- The Rules Directory

	- Homestead
		- Introduction
		- Installation & Setup
			- First Steps
			- Configuring Homestead
			- Launching The Vagrant Box
			- Per Project Installation
			- Installing MariaDB
			- Installing Elasticsearch
			- Aliases
		- Daily Usage
			- Accessing Homestead Globally
			- Connecting Via SSH
			- Connecting To Databases
			- Adding Additional Sites
			- Environment Variables
			- Configuring Cron Schedules
			- Configuring Mailhog
			- Ports
			- Sharing Your Environment
			- Multiple PHP Versions
			- Web Servers
		- Network Interfaces
		- Updating Homestead
		- Provider Specific Settings
			- VirtualBox

	- Valet
		- Introduction
			- Valet Or Homestead
		- Installation
			- Upgrading
		- Serving Sites
			- The "Park" Command
			- The "Link" Command
			- Securing Sites With TLS
		- Sharing Sites
		- Custom Valet Drivers
			- Local Drivers
		- Other Valet Commands

	- Deployment
		- Introduction
		- Server Configuration
			- Nginx
		- Optimization
			- Autoloader Optimization
			- Optimizing Configuration Loading
			- Optimizing Route Loading
		- Deploying With Forge

# Conceitos de arquitetura
	- Ciclo de Vida da Solicitação
		- Introduction
		- Lifecycle Overview
		- Focus On Service Providers

	- Contêiner de Serviço
		- Introduction
		- Binding
			- Binding Basics
			- Binding Interfaces To Implementations
			- Contextual Binding
			- Tagging
			- Extending Bindings
		- Resolving
			- The Make Method
			- Automatic Injection
		- Container Events
		- PSR-11

	- Provedores de serviço
		- Introduction
		- Writing Service Providers
			- The Register Method
			- The Boot Method
		- Registering Providers
		- Deferred Providers

	- Facades
		- Introduction
		- When To Use Facades
			- Facades Vs. Dependency Injection
			- Facades Vs. Helper Functions
		- How Facades Work
		- Real-Time Facades
		- Facade Class Reference

	- Contratos
		- Introduction
			- Contracts Vs. Facades
		- When To Use Contracts
			- Loose Coupling
			- Simplicity
		- How To Use Contracts
		- Contract Reference

# O básico
	- Roteamento
		- Basic Routing
			- Redirect Routes
			- View Routes
		- Route Parameters
			- Required Parameters
			- Optional Parameters
			- Regular Expression Constraints
		- Named Routes
		- Route Groups
			- Middleware
			- Namespaces
			- Sub-Domain Routing
			- Route Prefixes
			- Route Name Prefixes
		- Route Model Binding
			- Implicit Binding
			- Explicit Binding
		- Form Method Spoofing
		- Accessing The Current Route

	- Middleware
		- Introduction
		- Defining Middleware
		- Registering Middleware
			- Global Middleware
			- Assigning Middleware To Routes
			- Middleware Groups
		- Middleware Parameters
		- Terminable Middleware

	- Proteção CSRF
		- Introduction
		- Excluding URIs
		- X-CSRF-Token
		- X-XSRF-Token

	- controladores
		- Introduction
		- Basic Controllers
			- Defining Controllers
			- Controllers & Namespaces
			- Single Action Controllers
		- Controller Middleware
		- Resource Controllers
			- Partial Resource Routes
			- Naming Resource Routes
			- Naming Resource Route Parameters
			- Localizing Resource URIs
			- Supplementing Resource Controllers
		- Dependency Injection & Controllers
		- Route Caching


	- Requests
		- Accessing The Request
			- Request Path & Method
			- PSR-7 Requests
		- Input Trimming & Normalization
		- Retrieving Input
			- Old Input
			- Cookies
		- Files
			- Retrieving Uploaded Files
			- Storing Uploaded Files
		- Configuring Trusted Proxies

	- Responses
		- Creating Responses
			- Attaching Headers To Responses
			- Attaching Cookies To Responses
			- Cookies & Encryption
		- Redirects
			- Redirecting To Named Routes
			- Redirecting To Controller Actions
			- Redirecting To External Domains
			- Redirecting With Flashed Session Data
		- Other Response Types
			- View Responses
			- JSON Responses
			- File Downloads
			- File Responses
		- Response Macros

	- Views
		- Creating Views
		- Passing Data To Views
			- Sharing Data With All Views
		- View Composers

	- Geração de URL
		- Introduction
		- The Basics
			- Generating Basic URLs
			- Accessing The Current URL
		- URLs For Named Routes
		- URLs For Controller Actions
		- Default Values

	- Sessão
		- Introduction
			- Configuration
			- Driver Prerequisites
		- Using The Session
			- Retrieving Data
			- Storing Data
			- Flash Data
			- Deleting Data
			- Regenerating The Session ID
		- Adding Custom Session Drivers
			- Implementing The Driver
			- Registering The Driver

	- Validação
		- Introduction
		- Validation Quickstart
			- Defining The Routes
			- Creating The Controller
			- Writing The Validation Logic
			- Displaying The Validation Errors
			- A Note On Optional Fields
		- Form Request Validation
			- Creating Form Requests
			- Authorizing Form Requests
			- Customizing The Error Messages
		- Manually Creating Validators
			- Automatic Redirection
			- Named Error Bags
			- After Validation Hook
		- Working With Error Messages
			- Custom Error Messages
		- Available Validation Rules
		- Conditionally Adding Rules
		- Validating Arrays
		- Custom Validation Rules
			- Using Rule Objects
			- Using Extensions

	- Erros e registro
		- Introduction
		- Configuration
			- Error Detail
			- Log Storage
			- Log Severity Levels
			- Custom Monolog Configuration
		- The Exception Handler
			- Report Method
			- Render Method
			- Reportable & Renderable Exceptions
		- HTTP Exceptions
			- Custom HTTP Error Pages
		- Logging

# Frontend
	- Blade Templates
		- Introduction
		- Template Inheritance
			- Defining A Layout
			- Extending A Layout
		- Components & Slots
		- Displaying Data
			- Blade & JavaScript Frameworks
		- Control Structures
			- If Statements
			- Switch Statements
			- Loops
			- The Loop Variable
			- Comments
			- PHP
		- Including Sub-Views
			- Rendering Views For Collections
		- Stacks
		- Service Injection
		- Extending Blade
			- Custom If Statements

	- Localization
		- Introduction
		- Defining Translation Strings
			- Using Short Keys
			- Using Translation Strings As Keys
		- Retrieving Translation Strings
			- Replacing Parameters In Translation Strings
			- Pluralization
		- Overriding Package Language Files

	- Frontend Scaffolding
		- Introduction
		- Writing CSS
		- Writing JavaScript
			- Writing Vue Components
			- Using React

	- Compiling Assets
		- Introduction
		- Installation & Setup
		- Running Mix
		- Working With Stylesheets
			- Less
			- Sass
			- Stylus
			- PostCSS
			- Plain CSS
			- URL Processing
			- Source Maps
		- Working With JavaScript
			- Vendor Extraction
			- React
			- Vanilla JS
			- Custom Webpack Configuration
		- Copying Files & Directories
		- Versioning / Cache Busting
		- Browsersync Reloading
		- Environment Variables
		- Notifications

# Segurança
	- Autenticação
		- Introduction
			- Database Considerations
		- Authentication Quickstart
			- Routing
			- Views
			- Authenticating
			- Retrieving The Authenticated User
			- Protecting Routes
			- Login Throttling
		- Manually Authenticating Users
			- Remembering Users
			- Other Authentication Methods
		- HTTP Basic Authentication
			- Stateless HTTP Basic Authentication
		- Social Authentication
		- Adding Custom Guards
		- Adding Custom User Providers
			- The User Provider Contract
			- The Authenticatable Contract
		- Events

	- Autenticação da API
		- Introduction
		- Installation
			- Frontend Quickstart
			- Deploying Passport
		- Configuration
			- Token Lifetimes
		- Issuing Access Tokens
			- Managing Clients
			- Requesting Tokens
			- Refreshing Tokens
		- Password Grant Tokens
			- Creating A Password Grant Client
			- Requesting Tokens
			- Requesting All Scopes
		- Implicit Grant Tokens
		- Client Credentials Grant Tokens
		- Personal Access Tokens
			- Creating A Personal Access Client
			- Managing Personal Access Tokens
		- Protecting Routes
			- Via Middleware
			- Passing The Access Token
		- Token Scopes
			- Defining Scopes
			- Assigning Scopes To Tokens
			- Checking Scopes
		- Consuming Your API With JavaScript
		- Events
		- Testing

	- Autorização
		- Introduction
		- Gates
			- Writing Gates
			- Authorizing Actions
		- Creating Policies
			- Generating Policies
			- Registering Policies
		- Writing Policies
			- Policy Methods
			- Methods Without Models
			- Policy Filters
		- Authorizing Actions Using Policies
			- Via The User Model
			- Via Middleware
			- Via Controller Helpers
			- Via Blade Templates

	- Criptografia
		- Introduction
		- Configuration
		- Using The Encrypter

	- Hash
		- Introduction
		- Basic Usage

	- Redefinição de senha
		- Introduction
		- Database Considerations
		- Routing
		- Views
		- After Resetting Passwords
		- Customization

# Indo mais fundo
	- Artisan Console
		- Introduction
		- Writing Commands
			- Generating Commands
			- Command Structure
			- Closure Commands
		- Defining Input Expectations
			- Arguments
			- Options
			- Input Arrays
			- Input Descriptions
		- Command I/O
			- Retrieving Input
			- Prompting For Input
			- Writing Output
		- Registering Commands
		- Programmatically Executing Commands
			- Calling Commands From Other Commands

	- Broadcasting (Transmissão)
		- Introduction
			- Configuration
			- Driver Prerequisites
		- Concept Overview
			- Using An Example Application
		- Defining Broadcast Events
			- Broadcast Name
			- Broadcast Data
			- Broadcast Queue
			- Broadcast Conditions
		- Authorizing Channels
			- Defining Authorization Routes
			- Defining Authorization Callbacks
		- Broadcasting Events
			- Only To Others
		- Receiving Broadcasts
			- Installing Laravel Echo
			- Listening For Events
			- Leaving A Channel
			- Namespaces
		- Presence Channels
			- Authorizing Presence Channels
			- Joining Presence Channels
			- Broadcasting To Presence Channels
		- Client Events
		- Notifications

	- Cache
		- Configuration
			- Driver Prerequisites
		- Cache Usage
			- Obtaining A Cache Instance
			- Retrieving Items From The Cache
			- Storing Items In The Cache
			- Removing Items From The Cache
			- The Cache Helper
		- Cache Tags
			- Storing Tagged Cache Items
			- Accessing Tagged Cache Items
			- Removing Tagged Cache Items
		- Adding Custom Cache Drivers
			- Writing The Driver
			- Registering The Driver
		- Events

	- Collections
		- Introduction
			- Creating Collections
			- Extending Collections
		- Available Methods
		- Higher Order Messages

	- Events
		- Introduction
		- Registering Events & Listeners
			- Generating Events & Listeners
			- Manually Registering Events
		- Defining Events
		- Defining Listeners
		- Queued Event Listeners
			- Manually Accessing The Queue
			- Handling Failed Jobs
		- Dispatching Events
		- Event Subscribers
			- Writing Event Subscribers
			- Registering Event Subscribers

	- File Storage
		- Introduction
		- Configuration
			- The Public Disk
			- The Local Driver
			- Driver Prerequisites
		- Obtaining Disk Instances
		- Retrieving Files
			- File URLs
			- File Metadata
		- Storing Files
			- File Uploads
			- File Visibility
		- Deleting Files
		- Directories
		- Custom Filesystems

	- Helpers
		- Introduction
		- Available Methods

	- Mail
		- Introduction
			- Driver Prerequisites
		- Generating Mailables
		- Writing Mailables
			- Configuring The Sender
			- Configuring The View
			- View Data
			- Attachments
			- Inline Attachments
			- Customizing The SwiftMailer Message
		- Markdown Mailables
			- Generating Markdown Mailables
			- Writing Markdown Messages
			- Customizing The Components
		- Previewing Mailables In The Browser
		- Sending Mail
			- Queueing Mail
		- Mail & Local Development
		- Events

	- Notifications
		- Introduction
		- Creating Notifications
		- Sending Notifications
			- Using The Notifiable Trait
			- Using The Notification Facade
			- Specifying Delivery Channels
			- Queueing Notifications
			- On-Demand Notifications
		- Mail Notifications
			- Formatting Mail Messages
			- Customizing The Recipient
			- Customizing The Subject
			- Customizing The Templates
		- Markdown Mail Notifications
			- Generating The Message
			- Writing The Message
			- Customizing The Components
		- Database Notifications
			- Prerequisites
			- Formatting Database Notifications
			- Accessing The Notifications
			- Marking Notifications As Read
		- Broadcast Notifications
			- Prerequisites
			- Formatting Broadcast Notifications
			- Listening For Notifications
		- SMS Notifications
			- Prerequisites
			- Formatting SMS Notifications
			- Customizing The "From" Number
			- Routing SMS Notifications
		- Slack Notifications
			- Prerequisites
			- Formatting Slack Notifications
			- Slack Attachments
			- Routing Slack Notifications
		- Notification Events
		- Custom Channels

	- Package Development
		- Introduction
			- A Note On Facades
		- Package Discovery
		- Service Providers
		- Resources
			- Configuration
			- Migrations
			- Routes
			- Translations
			- Views
		- Commands
		- Public Assets
		- Publishing File Groups

	- Queues
		- Introduction
			- Connections Vs. Queues
			- Driver Prerequisites
		- Creating Jobs
			- Generating Job Classes
			- Class Structure
		- Dispatching Jobs
			- Delayed Dispatching
			- Job Chaining
			- Customizing The Queue & Connection
			- Specifying Max Job Attempts / Timeout Values
			- Rate Limiting
			- Error Handling
		- Running The Queue Worker
			- Queue Priorities
			- Queue Workers & Deployment
			- Job Expirations & Timeouts
		- Supervisor Configuration
		- Dealing With Failed Jobs
			- Cleaning Up After Failed Jobs
			- Failed Job Events
			- Retrying Failed Jobs
		- Job Events

	- Task Scheduling
		- Introduction
		- Defining Schedules
			- Scheduling Artisan Commands
			- Scheduling Queued Jobs
			- Scheduling Shell Commands
			- Schedule Frequency Options
			- Preventing Task Overlaps
			- Maintenance Mode
		- Task Output
		- Task Hooks

# Base de dados
	- Começando
		- Introduction
			- Configuration
			- Read & Write Connections
			- Using Multiple Database Connections
		- Running Raw SQL Queries
			- Listening For Query Events
		- Database Transactions

	- Construtor de consultas
		- Introduction
		- Retrieving Results
			- Chunking Results
			- Aggregates
		- Selects
		- Raw Expressions
		- Joins
		- Unions
		- Where Clauses
			- Parameter Grouping
			- Where Exists Clauses
			- JSON Where Clauses
		- Ordering, Grouping, Limit, & Offset
		- Conditional Clauses
		- Inserts
		- Updates
			- Updating JSON Columns
			- Increment & Decrement
		- Deletes
		- Pessimistic Locking

	- Paginação
		- Introduction
		- Basic Usage
			- Paginating Query Builder Results
			- Paginating Eloquent Results
			- Manually Creating A Paginator
		- Displaying Pagination Results
			- Converting Results To JSON
		- Customizing The Pagination View
		- Paginator Instance Methods

	- Migrações
		- Introduction
		- Generating Migrations
		- Migration Structure
		- Running Migrations
			- Rolling Back Migrations
		- Tables
			- Creating Tables
			- Renaming / Dropping Tables
		- Columns
			- Creating Columns
			- Column Modifiers
			- Modifying Columns
			- Dropping Columns
		- Indexes
			- Creating Indexes
			- Dropping Indexes
			- Foreign Key Constraints

	- Semeando
		- Introduction
		- Writing Seeders
			- Using Model Factories
			- Calling Additional Seeders
		- Running Seeders

	- Redis
		- Introduction
			- Configuration
			- Predis
			- PhpRedis
		- Interacting With Redis
			- Pipelining Commands
		- Pub / Sub

# Eloquente ORM
	- Começando
		- Introduction
		- Defining Models
			- Eloquent Model Conventions
		- Retrieving Models
			- Collections
			- Chunking Results
		- Retrieving Single Models / Aggregates
			- Retrieving Aggregates
		- Inserting & Updating Models
			- Inserts
			- Updates
			- Mass Assignment
			- Other Creation Methods
		- Deleting Models
			- Soft Deleting
			- Querying Soft Deleted Models
		- Query Scopes
			- Global Scopes
			- Local Scopes
		- Events
			- Observers

	- Relacionamentos
		- Introduction
		- Defining Relationships
			- One To One
			- One To Many
			- One To Many (Inverse)
			- Many To Many
			- Has Many Through
			- Polymorphic Relations
			- Many To Many Polymorphic Relations
		- Querying Relations
			- Relationship Methods Vs. Dynamic Properties
			- Querying Relationship Existence
			- Querying Relationship Absence
			- Counting Related Models
		- Eager Loading
			- Constraining Eager Loads
			- Lazy Eager Loading
		- Inserting & Updating Related Models
			- The save Method
			- The create Method
			- Belongs To Relationships
			- Many To Many Relationships
		- Touching Parent Timestamps

	- Coleções
		Introduction
		Available Methods
		Custom Collections

	- Mutadores
		- Introduction
		- Accessors & Mutators
			- Defining An Accessor
			- Defining A Mutator
		- Date Mutators
		- Attribute Casting
			- Array & JSON Casting

	- Recursos da API
		- Introduction
		- Generating Resources
		- Concept Overview
		- Writing Resources
			- Data Wrapping
			- Pagination
			- Conditional Attributes
			- Conditional Relationships
			- Adding Meta Data
		Resource Responses

	- Serialização
		- Introduction
		- Serializing Models & Collections
			- Serializing To Arrays
			- Serializing To JSON
		- Hiding Attributes From JSON
		- Appending Values To JSON
		- Date Serialization

# teste
	- Começando
		- Introduction
		- Environment
		- Creating & Running Tests

	- Testes HTTP
		- Introduction
			- Customizing Request Headers
		- Session / Authentication
		- Testing JSON APIs
		- Testing File Uploads
		- Available Assertions
			- Response Assertions
			- Authentication Assertions

	- Testes de navegador
		- Introduction
		- Installation
			- Using Other Browsers
		- Getting Started
			- Generating Tests
			- Running Tests
			- Environment Handling
			- Creating Browsers
			- Authentication
			- Database Migrations
		- Interacting With Elements
			- Dusk Selectors
			- Clicking Links
			- Text, Values, & Attributes
			- Using Forms
			- Attaching Files
			- Using The Keyboard
			- Using The Mouse
			- Scoping Selectors
			- Waiting For Elements
			- Making Vue Assertions
		- Available Assertions
			- Pages
			- Generating Pages
			- Configuring Pages
			- Navigating To Pages
			- Shorthand Selectors
			- Page Methods
		- Components
			- Generating Components
			- Using Components
		- Continuous Integration
			- Travis CI
			- CircleCI
			- Codeship

	- Base de dados
		- Introduction
		- Generating Factories
		- Resetting The Database After Each Test
		- Writing Factories
			- Factory States
		- Using Factories
			- Creating Models
			- Persisting Models
			- Relationships
		- Available Assertions

	- zombando
		- Introduction
		- Bus Fake
		- Event Fake
		- Mail Fake
		- Notification Fake
		- Queue Fake
		- Storage Fake
		- Facades

# Pacotes Oficiais
	- Cashier
		- Introduction
		- Configuration
			- Stripe
			- Braintree
			- Currency Configuration
		- Subscriptions
			- Creating Subscriptions
			- Checking Subscription Status
			- Changing Plans
			- Subscription Quantity
			- Subscription Taxes
			- Cancelling Subscriptions
			- Resuming Subscriptions
			- Updating Credit Cards
		- Subscription Trials
			- With Credit Card Up Front
			- Without Credit Card Up Front
		- Handling Stripe Webhooks
			- Defining Webhook Event Handlers
			- Failed Subscriptions
		- Handling Braintree Webhooks
			- Defining Webhook Event Handlers
			- Failed Subscriptions
		- Single Charges
		- Invoices
			- Generating Invoice PDFs

	- Envoy
		- Introduction
			- Installation
		- Writing Tasks
			- Setup
			- Variables
			- Stories
			- Multiple Servers
		- Running Tasks
			- Confirming Task Execution
		- Notifications
			- Slack

	- Horizon
		- Introduction
		- Installation
			- Configuration
			- Dashboard Authentication
		- Running Horizon
			- Deploying Horizon
		- Tags
		- Notifications
		- Metrics

	- Passport
		- Introduction
		- Installation
			- Frontend Quickstart
			- Deploying Passport
		- Configuration
			- Token Lifetimes
		- Issuing Access Tokens
			- Managing Clients
			- Requesting Tokens
			- Refreshing Tokens
		- Password Grant Tokens
			- Creating A Password Grant Client
			- Requesting Tokens
			- Requesting All Scopes
		- Implicit Grant Tokens
		- Client Credentials Grant Tokens
		- Personal Access Tokens
			- Creating A Personal Access Client
			- Managing Personal Access Tokens
		- Protecting Routes
			- Via Middleware
			- Passing The Access Token
		- Token Scopes
			- Defining Scopes
			- Assigning Scopes To Tokens
			- Checking Scopes
		- Consuming Your API With JavaScript
		- Events
		- Testing

	- Scout
		- Introduction
		- Installation
			- Queueing
			- Driver Prerequisites
		- Configuration
			- Configuring Model Indexes
			- Configuring Searchable Data
		- Indexing
			- Batch Import
			- Adding Records
			- Updating Records
			- Removing Records
			- Pausing Indexing
		- Searching
			- Where Clauses
			- Pagination
		- Custom Engines

	- Socialite
		- Introduction
		- Installation
		- Configuration
		- Routing
		- Optional Parameters
		- Access Scopes
		- Stateless Authentication
		- Retrieving User Details