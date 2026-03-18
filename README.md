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

# Server Metrics 2026-03-18 17:51:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8780.3 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250637
telemt_connections_bad_total 16232
telemt_handshake_timeouts_total 6178
telemt_upstream_connect_attempt_total 1399
telemt_upstream_connect_success_total 1399
telemt_upstream_connect_attempts_per_request{bucket="1"} 1399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 942
telemt_me_reconnect_success_total 938
telemt_me_reader_eof_total 966
telemt_me_idle_close_by_peer_total 966
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 115670
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212718
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1178
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 819
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 958
telemt_me_writer_restored_same_endpoint_total 925
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 212623
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 2994834272 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 71259828540 (66.37 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 13608.2 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1383061
telemt_connections_bad_total 84669
telemt_connections_current 3521
telemt_connections_me_current 3521
telemt_handshake_timeouts_total 26924
telemt_upstream_connect_attempt_total 2363
telemt_upstream_connect_success_total 2350
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1631
telemt_me_reconnect_success_total 1617
telemt_me_reader_eof_total 1584
telemt_me_idle_close_by_peer_total 1583
telemt_me_route_drop_no_conn_total 1457434
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1202493
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3567
telemt_desync_full_logged_total 1131
telemt_desync_suppressed_total 2436
telemt_desync_frames_bucket_total{bucket="1_2"} 649
telemt_desync_frames_bucket_total{bucket="3_10"} 1412
telemt_desync_frames_bucket_total{bucket="gt_10"} 1506
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1555
telemt_me_writer_restored_same_endpoint_total 1615
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1197797
telemt_user_connections_current{user="hello"} 3521
telemt_user_octets_from_client{user="hello"} 15574342704 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 348296598052 (324.38 GB)
telemt_user_unique_ips_current{user="hello"} 1128
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 13536.8 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961033
telemt_connections_bad_total 76920
telemt_connections_current 3124
telemt_connections_me_current 3124
telemt_handshake_timeouts_total 21358
telemt_upstream_connect_attempt_total 1885
telemt_upstream_connect_success_total 1875
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1187
telemt_me_reconnect_success_total 1175
telemt_me_reader_eof_total 1241
telemt_me_idle_close_by_peer_total 1241
telemt_me_route_drop_no_conn_total 433317
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 794523
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3332
telemt_desync_full_logged_total 1023
telemt_desync_suppressed_total 2309
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 1241
telemt_desync_frames_bucket_total{bucket="gt_10"} 1262
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_restored_same_endpoint_total 1158
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 794163
telemt_user_connections_current{user="hello"} 3124
telemt_user_octets_from_client{user="hello"} 19189883724 (17.87 GB)
telemt_user_octets_to_client{user="hello"} 340817773876 (317.41 GB)
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 14250.9 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1434543
telemt_connections_bad_total 33521
telemt_connections_current 2900
telemt_connections_me_current 2900
telemt_handshake_timeouts_total 16284
telemt_upstream_connect_attempt_total 2176
telemt_upstream_connect_success_total 2160
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1435
telemt_me_reconnect_success_total 1417
telemt_me_reader_eof_total 1450
telemt_me_idle_close_by_peer_total 1449
telemt_me_route_drop_no_conn_total 2411963
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1281417
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4804
telemt_desync_full_logged_total 1205
telemt_desync_suppressed_total 3599
telemt_desync_frames_bucket_total{bucket="1_2"} 1107
telemt_desync_frames_bucket_total{bucket="3_10"} 2241
telemt_desync_frames_bucket_total{bucket="gt_10"} 1456
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1416
telemt_me_writer_restored_same_endpoint_total 1406
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1281339
telemt_user_connections_current{user="hello"} 2900
telemt_user_octets_from_client{user="hello"} 12286700216 (11.44 GB)
telemt_user_octets_to_client{user="hello"} 213033534484 (198.40 GB)
telemt_user_unique_ips_current{user="hello"} 899
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8765.7 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660503
telemt_connections_bad_total 124767
telemt_handshake_timeouts_total 6412
telemt_upstream_connect_attempt_total 1580
telemt_upstream_connect_success_total 1528
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 1580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 3152
telemt_me_reconnect_success_total 1063
telemt_me_reader_eof_total 1132
telemt_me_idle_close_by_peer_total 1132
telemt_me_route_drop_no_conn_total 258161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480742
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1185
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 604
telemt_desync_frames_bucket_total{bucket="gt_10"} 860
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1142
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1037
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 480244
telemt_user_connections_current{user="hello"} 3159
telemt_user_octets_from_client{user="hello"} 7725708568 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 204342275536 (190.31 GB)
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 429
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 13701.7 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250323
telemt_connections_bad_total 9818
telemt_connections_current 780
telemt_connections_me_current 780
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2702
telemt_upstream_connect_attempt_total 6480
telemt_upstream_connect_success_total 6465
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 331371
telemt_me_reconnect_success_total 1905
telemt_me_reader_eof_total 1893
telemt_me_idle_close_by_peer_total 1893
telemt_me_route_drop_no_conn_total 161805
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221624
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 434
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 11
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 1848
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1894
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 225341
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 3367312137 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 45994822281 (42.84 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 12770.2 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 770729
telemt_connections_bad_total 54364
telemt_connections_current 2721
telemt_connections_me_current 2721
telemt_handshake_timeouts_total 14293
telemt_upstream_connect_attempt_total 2246
telemt_upstream_connect_success_total 2245
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17067
telemt_me_reconnect_success_total 1553
telemt_me_reader_eof_total 1543
telemt_me_idle_close_by_peer_total 1543
telemt_me_route_drop_no_conn_total 415313
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646852
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2514
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1650
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 887
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1518
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1492
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 645876
telemt_user_connections_current{user="hello"} 2721
telemt_user_octets_from_client{user="hello"} 12184676576 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 321503958852 (299.42 GB)
telemt_user_unique_ips_current{user="hello"} 870
telemt_user_unique_ips_recent_window{user="hello"} 355
```