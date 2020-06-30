# List of practiced topics
- Configure hibernate xml file (hibernate.cfg.xml)
- CRUD features
- SessionFactory and Session
- Start and commit a Transaction
- Add no-arg constructor for entity class.
- @Entity [javax.persistence]
- @Id
- @GeneratedValue: GenerationType.IDENTITY
- @Table: map to table in the database [javax.persistence]
- @Column: map to column of the table
- @OneToOne: uni-directional (use @JoinColumn) and bi-directional (use 'mappedBy')
- @OneToMany
- 'mappedBy' attribute: used in the class entity which does not contain the foreign key.
- @JoinColum: used in the table class entity containing the foreign key.
- Cascade types: CascadeType.ALL, CascadeType.PERSIST (save), CascadeType.REMOVE
- Handle connection leak issue: catch error and close session.
- {Tip} Add convenience methods for bi-directional one-to-many relationship
- {Tip} Use persist with CascadeType.ALL/PERSIST to save all assorciated objects in one-to-many relationship.
