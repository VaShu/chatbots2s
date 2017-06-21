=== My note ===

Creating vocabulary /home/vadim/pypro/bot_tfs2s/data/vocab20000.in from data /home/vadim/pypro/bot_tfs2s/data/chat.in
  processing line 100000
  processing line 200000
  processing line 300000
  processing line 400000
Tokenizing data in /home/vadim/pypro/bot_tfs2s/data/chat.in
  tokenizing line 100000
  tokenizing line 200000
  tokenizing line 300000
  tokenizing line 400000
Tokenizing data in /home/vadim/pypro/bot_tfs2s/data/chat_test.in

Creating 1 layers of 128 units.
WARNING:tensorflow:From /home/vadim/pypro/bot_tfs2s/tf_seq2seq_chatbot/lib/seq2seq_model.py:166 in __init__.:
all_variables (from tensorflow.python.ops.variables) is deprecated and will be removed after 2017-03-02.
Instructions for updating:
Please use tf.global_variables instead.

Created model with fresh parameters.
WARNING:tensorflow:From /home/vadim/pypro/bot_tfs2s/tf_seq2seq_chatbot/lib/seq2seq_model_utils.py:35 in create_model.:
initialize_all_variables (from tensorflow.python.ops.variables) is deprecated and will be removed after 2017-03-02.
Instructions for updating:
Use `tf.global_variables_initializer` instead.

###
In ...env/lib64/python3.5/site-packages/tensorflow/python/util/compat.py
line 84:
    return bytes_or_text.decode(encoding)
replace on:
    return bytes_or_text.decode(encoding, "ignore")
###
git clone git@github.com:nicolas-ivanov/tf_seq2seq_chatbot.git bot_tfs2s
python3 -m venv bots2_env
git remote add vashu git@github.com:VaShu/chatbots2s.git
git remote -v
git push vashu master
