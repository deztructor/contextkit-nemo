SUBDIRS = bluez session profile kbslider customer-tests

coverage: covoptioncheck
	$(MAKE) -C customer-tests coverage

check-customer:
	$(MAKE) -C customer-tests check-customer

include $(top_srcdir)/am/covoptioncheck.am
