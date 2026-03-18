# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 13:45:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 18276.1 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681167
telemt_connections_bad_total 33144
telemt_handshake_timeouts_total 18564
telemt_upstream_connect_attempt_total 66503
telemt_upstream_connect_success_total 65545
telemt_upstream_connect_fail_total 958
telemt_upstream_connect_attempts_per_request{bucket="1"} 66503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 958
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514273
telemt_me_reconnect_success_total 2620
telemt_me_reader_eof_total 2790
telemt_me_idle_close_by_peer_total 2788
telemt_me_route_drop_no_conn_total 387482
telemt_me_route_drop_channel_closed_total 149
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524851
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2317
telemt_desync_full_logged_total 799
telemt_desync_suppressed_total 1518
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 874
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2793
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2515
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 583030
telemt_user_connections_current{user="hello"} 1775
telemt_user_octets_from_client{user="hello"} 8067238112 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 149453894713 (139.19 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 18307.2 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795212
telemt_connections_bad_total 124047
telemt_handshake_timeouts_total 40555
telemt_upstream_connect_attempt_total 3249
telemt_upstream_connect_success_total 3237
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3375
telemt_me_reconnect_success_total 2229
telemt_me_reader_eof_total 2314
telemt_me_idle_close_by_peer_total 2313
telemt_me_route_drop_no_conn_total 1425063
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1541818
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4759
telemt_desync_full_logged_total 1501
telemt_desync_suppressed_total 3258
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 1933
telemt_desync_frames_bucket_total{bucket="gt_10"} 1864
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2280
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2228
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1540809
telemt_user_connections_current{user="hello"} 4738
telemt_user_octets_from_client{user="hello"} 37052773104 (34.51 GB)
telemt_user_octets_to_client{user="hello"} 476971800036 (444.21 GB)
telemt_user_unique_ips_current{user="hello"} 1376
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 18222.2 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1317006
telemt_connections_bad_total 99492
telemt_handshake_timeouts_total 29486
telemt_upstream_connect_attempt_total 11788
telemt_upstream_connect_success_total 11788
telemt_upstream_connect_attempts_per_request{bucket="1"} 11788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 612197
telemt_me_reconnect_success_total 2592
telemt_me_reader_eof_total 2741
telemt_me_idle_close_by_peer_total 2740
telemt_me_route_drop_no_conn_total 639336
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1028065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3212
telemt_desync_full_logged_total 1064
telemt_desync_suppressed_total 2148
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1156
telemt_desync_frames_bucket_total{bucket="gt_10"} 1164
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2731
telemt_me_refill_failed_total 19794
telemt_me_writer_restored_same_endpoint_total 2557
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1035547
telemt_user_connections_current{user="hello"} 3278
telemt_user_octets_from_client{user="hello"} 13295544475 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 421523906108 (392.57 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 18252.3 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2122274
telemt_connections_bad_total 33728
telemt_handshake_timeouts_total 176806
telemt_upstream_connect_attempt_total 12650
telemt_upstream_connect_success_total 12436
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 12650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2835314
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1890
telemt_me_route_drop_no_conn_total 3267130
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1748413
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3712
telemt_desync_full_logged_total 1095
telemt_desync_suppressed_total 2617
telemt_desync_frames_bucket_total{bucket="1_2"} 945
telemt_desync_frames_bucket_total{bucket="3_10"} 1566
telemt_desync_frames_bucket_total{bucket="gt_10"} 1201
telemt_me_writer_removed_unexpected_total 1939
telemt_me_refill_failed_total 100304
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 1766866
telemt_user_connections_current{user="hello"} 2791
telemt_user_octets_from_client{user="hello"} 40370352062 (37.60 GB)
telemt_user_octets_to_client{user="hello"} 254959891649 (237.45 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 18147.1 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1430672
telemt_connections_bad_total 100474
telemt_handshake_timeouts_total 23658
telemt_upstream_connect_attempt_total 14775
telemt_upstream_connect_success_total 14747
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 14775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986568
telemt_me_reconnect_success_total 2132
telemt_me_reader_eof_total 2234
telemt_me_idle_close_by_peer_total 2234
telemt_me_route_drop_no_conn_total 1314005
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1192355
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3636
telemt_desync_full_logged_total 1240
telemt_desync_suppressed_total 2396
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 1405
telemt_desync_frames_bucket_total{bucket="gt_10"} 1664
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2197
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2017
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1194277
telemt_user_connections_current{user="hello"} 3169
telemt_user_octets_from_client{user="hello"} 19054625619 (17.75 GB)
telemt_user_octets_to_client{user="hello"} 425031447421 (395.84 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1019
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 18033.4 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404802
telemt_connections_bad_total 44727
telemt_handshake_timeouts_total 2974
telemt_upstream_connect_attempt_total 3308
telemt_upstream_connect_success_total 3308
telemt_upstream_connect_attempts_per_request{bucket="1"} 3308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8792
telemt_me_reconnect_success_total 2338
telemt_me_reader_eof_total 2582
telemt_me_idle_close_by_peer_total 2581
telemt_me_route_drop_no_conn_total 227299
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339274
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 892
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2562
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2329
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 329539
telemt_user_connections_current{user="hello"} 965
telemt_user_octets_from_client{user="hello"} 5029228132 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 68621641184 (63.91 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 18103.1 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158110
telemt_connections_bad_total 127201
telemt_handshake_timeouts_total 23235
telemt_upstream_connect_attempt_total 3359
telemt_upstream_connect_success_total 3330
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 3440
telemt_me_reconnect_success_total 2338
telemt_me_reader_eof_total 2428
telemt_me_idle_close_by_peer_total 2428
telemt_me_route_drop_no_conn_total 673849
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916552
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3083
telemt_desync_full_logged_total 1030
telemt_desync_suppressed_total 2053
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 1043
telemt_desync_frames_bucket_total{bucket="gt_10"} 1471
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2392
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 2328
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 915927
telemt_user_connections_current{user="hello"} 3029
telemt_user_octets_from_client{user="hello"} 18691856300 (17.41 GB)
telemt_user_octets_to_client{user="hello"} 415936436948 (387.37 GB)
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 412
```