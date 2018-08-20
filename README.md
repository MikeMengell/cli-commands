###GCP Commands

`gcloud auth list` - Lists accounts and shows current active


###Prometheus Queries

'sum(sort_desc(sum_over_time(ALERTS{alertstate=`firing`}[3d]))) by (alertname)' - Show all alerts fired over period
