#!/bin/bash

if [ $# == 0 ]; then
echo "/root/script.sh Redhat | Centos"
exit
fi
if [ $1 == Redhat ]; then
echo " Centos "
elif [ $1 == Centos ]
then
echo " Redhat "
else
echo "/root/script.sh Redhat | Centos"
fi
