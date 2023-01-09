#!/bin/bash

# If running the rails server then create or migrate existing database
if [ "${*}" == "./bin/rails server" ]; then
  ./bin/rails db:create
  ./bin/rails db:prepare
fi

exec "${@}"
