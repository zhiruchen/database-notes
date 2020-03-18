## Buffer Pool

### handling dirty page

* Buffer Manager will use ***dirty bit*** to find out the dirty page

* Buffer Manager will write back dirty page to disk via Disk Manager


### Page Replacement

* buffer manager use ***pin count*** to know if a page is in use.

* when buffer poll is full, buffer manager will use ***page replacement policy*** to replace that page. 


### Page Replacement Policy

* Least-recently-Used(LRU), Clock

* Most-recently-used(MRU)

* policy have big impact on I/Os.(depends on access pattern).

### LRU

* pinned frame not used for replacement.

* replace the frame that least recently used.

### Clock Policy

* Squential Flooding


### MRU

### Prefetch
