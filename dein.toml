[[plugins]]
repo = 'Shougo/dein.vim'

[[plugins]]
repo = 'tpope/vim-endwise'

[[plugins]]
repo = 'Townk/vim-autoclose'

[[plugins]]
repo = 'joshdick/onedark.vim'
hook_add = '''
  colorscheme onedark
'''

[[plugins]]
repo = 'w0rp/ale'

[[plugins]]
repo = 'airblade/vim-gitgutter'
hook_add = '''
  set signcolumn=yes
  set updatetime=1000
  nnoremap [gitgutter] <Nop>
  nmap <C-h> [gitgutter]
  nmap [gitgutter]j <Plug>GitGutterNextHunk
  nmap [gitgutter]k <Plug>GitGutterPrevHunk
  nmap [gitgutter]u <Plug>GitGutterUndoHunk
'''

[[plugins]]
repo = 'tpope/vim-fugitive'
hook_add = '''
  command Gst :Gstatus
  command Gdf :Gdiff
  command Gbl :Gblame
'''

[[plugins]]
repo = 'Shougo/denite.nvim'
hook_add = '''
  nnoremap [denite] <Nop>
  nmap <C-d> [denite]
  nnoremap <silent> [denite]g :<C-u>Denite grep -buffer-name=search-buffer-denite<CR>
  nnoremap <silent> [denite]r :<C-u>Denite -resume -buffer-name=search-buffer-denite<CR>
  nnoremap <silent> [denite]p :<C-u>Denite file_rec<CR>
  call denite#custom#option('default', 'prompt', '>')
  call denite#custom#option('_', 'highlight_matched_range', 'None')
  call denite#custom#option('_', 'highlight_matched_char', 'None')
  call denite#custom#map('insert', "<Tab>", '<denite:move_to_next_line>')
  call denite#custom#map('insert', "<S-Tab>", '<denite:move_to_previous_line>')
  call denite#custom#map('insert', "<C-t>", '<denite:do_action:tabopen>')
  call denite#custom#map('insert', "<C-v>", '<denite:do_action:vsplit>')
  call denite#custom#map('normal', "v", '<denite:do_action:vsplit>')
  call denite#custom#var('grep', 'command', ['pt', '--follow', '--nogroup', '--nocolor', '--hidden'])
  call denite#custom#var('grep', 'default_opts', [])
  call denite#custom#var('grep', 'recursive_opts', [])
  call denite#custom#var('file_rec', 'command', ['pt', '--follow', '--nocolor', '--nogroup', '--hidden', '-g', ''])
'''

[[plugins]]
repo = 'osyo-manga/vim-anzu'
hook_add = '''
  nmap n <Plug>(anzu-n-with-echo)
  nmap N <Plug>(anzu-N-with-echo)
  nmap * <Plug>(anzu-star)
  nmap # <Plug>(anzu-sharp)
'''
