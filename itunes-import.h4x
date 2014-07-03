#!/bin/bash
if [ $# -lt 1 ]
then
  echo 'Usage:  itunes-import source'
  exit
fi

for file in "$@"
do
  echo "Importing: $file"
  cp "$file" $HOME/Music/iTunes/iTunes\ Media/Automatically\ Add\ to\ iTunes.localized/
  rm "$file"
done
