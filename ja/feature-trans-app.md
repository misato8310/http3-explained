## トランスポートとアプリケーションレベル

IETF QUIC プロトコルはトランスポートプロトコルであり、その上に他のアプリケーションプロトコルも使用可能です。
最も主要なアプリケーションレイヤプロトコルは HTTP/3(h3) です。

トランスポートレイヤではコネクションとストリームをサポートします。

従来の Google 版の QUIC はトランスポートと HTTP が一括で動作するよう一つにまとめられており、
HTTP/2 フレームを UDP 上で送ることにより特化したプロトコルでした。
