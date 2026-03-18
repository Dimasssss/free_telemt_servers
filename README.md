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

# Server Metrics 2026-03-18 00:10:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 105925.2 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252457
telemt_connections_bad_total 9416
telemt_handshake_timeouts_total 32391
telemt_upstream_connect_attempt_total 23747
telemt_upstream_connect_success_total 23250
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 23747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32813
telemt_me_reconnect_success_total 15678
telemt_me_reader_eof_total 17028
telemt_me_idle_close_by_peer_total 17027
telemt_me_route_drop_no_conn_total 553197
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1150710
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7501
telemt_desync_full_logged_total 2194
telemt_desync_suppressed_total 5307
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 2843
telemt_desync_frames_bucket_total{bucket="gt_10"} 2651
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16445
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15656
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 767
telemt_user_connections_total{user="hello"} 1144924
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 22669689995 (21.11 GB)
telemt_user_octets_to_client{user="hello"} 411859133975 (383.57 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 106176.4 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1329177
telemt_connections_bad_total 61550
telemt_handshake_timeouts_total 45768
telemt_upstream_connect_attempt_total 465534
telemt_upstream_connect_success_total 463992
telemt_upstream_connect_fail_total 1542
telemt_upstream_connect_attempts_per_request{bucket="1"} 465534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 388364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1542
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 121908
telemt_me_reconnect_success_total 16479
telemt_me_reader_eof_total 18557
telemt_me_idle_close_by_peer_total 18547
telemt_me_route_drop_no_conn_total 344459
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 712347
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3256
telemt_desync_full_logged_total 1075
telemt_desync_suppressed_total 2181
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1338
telemt_desync_frames_bucket_total{bucket="gt_10"} 1287
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 18024
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16461
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1545
telemt_user_connections_total{user="hello"} 1154005
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 15735334381 (14.65 GB)
telemt_user_octets_to_client{user="hello"} 395856747904 (368.67 GB)
telemt_user_msgs_from_client{user="hello"} 7465941
telemt_user_msgs_to_client{user="hello"} 31929637
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 105952.4 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 785423
telemt_connections_bad_total 50505
telemt_handshake_timeouts_total 23822
telemt_upstream_connect_attempt_total 24889
telemt_upstream_connect_success_total 24745
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 24889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40100
telemt_me_reconnect_success_total 19418
telemt_me_reader_eof_total 21158
telemt_me_idle_close_by_peer_total 21151
telemt_me_route_drop_no_conn_total 318919
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667627
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2136
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 20330
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19406
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 912
telemt_user_connections_total{user="hello"} 665845
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 32043572604 (29.84 GB)
telemt_user_octets_to_client{user="hello"} 294479062776 (274.25 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 106012.0 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1273105
telemt_connections_bad_total 51199
telemt_handshake_timeouts_total 21718
telemt_upstream_connect_attempt_total 86063
telemt_upstream_connect_success_total 84648
telemt_upstream_connect_fail_total 1415
telemt_upstream_connect_attempts_per_request{bucket="1"} 86063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1415
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35711
telemt_me_reconnect_success_total 15351
telemt_me_reader_eof_total 16949
telemt_me_idle_close_by_peer_total 16947
telemt_me_route_drop_no_conn_total 521929
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036873
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3903
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 2613
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1643
telemt_desync_frames_bucket_total{bucket="gt_10"} 1310
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 16278
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15341
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 927
telemt_user_connections_total{user="hello"} 1099998
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 17267639251 (16.08 GB)
telemt_user_octets_to_client{user="hello"} 508352430166 (473.44 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 105983.8 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829684
telemt_connections_bad_total 97932
telemt_handshake_timeouts_total 6686
telemt_upstream_connect_attempt_total 43895
telemt_upstream_connect_success_total 43294
telemt_upstream_connect_fail_total 601
telemt_upstream_connect_attempts_per_request{bucket="1"} 43895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 410
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 601
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56483
telemt_me_reconnect_success_total 21526
telemt_me_reader_eof_total 23413
telemt_me_idle_close_by_peer_total 23411
telemt_me_route_drop_no_conn_total 262991
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 666977
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3159
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 2224
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1261
telemt_desync_frames_bucket_total{bucket="gt_10"} 896
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22973
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21518
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1447
telemt_user_connections_total{user="hello"} 683585
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 13475688704 (12.55 GB)
telemt_user_octets_to_client{user="hello"} 342701297632 (319.17 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 106145.0 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066412
telemt_connections_bad_total 99564
telemt_handshake_timeouts_total 9579
telemt_upstream_connect_attempt_total 21047
telemt_upstream_connect_success_total 20931
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 21047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26935
telemt_me_reconnect_success_total 15653
telemt_me_reader_eof_total 16990
telemt_me_idle_close_by_peer_total 16988
telemt_me_route_drop_no_conn_total 717102
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032908
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 92
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16258
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15639
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 889138
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 14318099660 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 376923844608 (351.04 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 53912.1 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386317
telemt_connections_bad_total 44669
telemt_handshake_timeouts_total 10797
telemt_upstream_connect_attempt_total 20317
telemt_upstream_connect_success_total 20133
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 20317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28892
telemt_me_reconnect_success_total 17293
telemt_me_reader_eof_total 18287
telemt_me_idle_close_by_peer_total 18287
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 96707
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286786
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1069
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17854
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17263
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 286727
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 22074964053 (20.56 GB)
telemt_user_octets_to_client{user="hello"} 235701225058 (219.51 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 24
```