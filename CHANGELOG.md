# Changelog

## 3.0.0
### Breaking changes
- Minimum version of PHP 8.1 required

`EncryptionSubscriber.php`
If you use your own EncryptionSubscriber:
All type declared values for the Doctrine manager have been changed from `ObjectManager $entityManager` to also support the EntityManager: `ObjectManager|EntityManager $entityManager` 
