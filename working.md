# 1 
install laravel app

# 2
install breeze
    > composer require laravel/breeze --dev
    >  php artisan breeze:install

# 3 

install livewire

then add livewireStyles and Scripts in layout file (app.layout)

then install npm

# 4 

create chat index

    > php artisan make:livewire chat.index
then create a outline structure in chat index

# 5 

create a avatar component in views/components and paste the code from source code

# 6 

create livewire component chat-list 

include that in index.. 

and made some changes and tailwind in chat-list

# 7 

we are working on chat-list (chat list item)

# 8 

we are creating a new livewire component chat

we are doing here main chat with chat id's -> like this ...  Route::get('/chat/{query}', Chat::class)->name('chat');
