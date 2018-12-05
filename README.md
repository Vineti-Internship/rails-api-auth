                   Prefix Verb   URI Pattern                                                                              Controller#Action
             authenticate POST   /authenticate(.:format)                                                                  authentication#authenticate
                    items GET    /items(.:format)                                                                         items#index
                          POST   /items(.:format)                                                                         items#create
                     item GET    /items/:id(.:format)                                                                     items#show
                          PATCH  /items/:id(.:format)                                                                     items#update
                          PUT    /items/:id(.:format)                                                                     items#update
                          DELETE /items/:id(.:format)                                                                     items#destroy
