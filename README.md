im-in.space is moving to a much needed new server. Its name: [Rosetta](https://rosetta.im-in.space).

## Progress
- [x] Get the new server
- [x] Basic configuration
- [ ] Setup new backup

### Mastodon

**Shutdown and moving starting Saturday May 30th at 14:00 CET (8am ET).**

- [x] Installation of Mastodon
  - [x] Bonus: Elasticsearch
- [x] Copy of our .env
- [x] First transfert of the attachments
- [x] Stop the instance
- [x] Change DNS
- [x] Dump the DB for transfert
- [x] Transfert the DB to the new server
- [x] Restore of the DB
- [x] First start of Mastodon on the new server
- [x] Rebuild of the users' timelines
- [x] Build of the Elasticsearch index
- [ ] => **Transfert of possible remaining attachments in the background**
  - _+ fixing perms so image do load_

### Pleroma

**Migration of Pleroma not yet planned.**

- [ ] Installation of Pleroma
- [ ] Copy of our .env
- [ ] First transfert of the attachments
- [ ] Stop the instance and dump DB
- [ ] Change DNS
- [ ] Transfert and restore of the DB
- [ ] Transfert of possible remaining attachments
- [ ] First start of Pleroma on the new server
