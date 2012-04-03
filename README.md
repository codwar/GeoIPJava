GEO IP
=======

Sample Usage
-------------

    * Country Lookup

    LookupService cl = new LookupService(dbfile,LookupService.GEOIP_MEMORY_CACHE);
    cl.getCountry("151.38.39.114").getCode()
    cl.getCountry("151.38.39.114").getName()
    cl.close()

    * See samples directory for more
