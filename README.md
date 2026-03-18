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

# Server Metrics 2026-03-18 02:48:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 115396.7 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1328658
telemt_connections_bad_total 10365
telemt_handshake_timeouts_total 33201
telemt_upstream_connect_attempt_total 25611
telemt_upstream_connect_success_total 25102
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 25611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34188
telemt_me_reconnect_success_total 17047
telemt_me_reader_eof_total 18505
telemt_me_idle_close_by_peer_total 18504
telemt_me_route_drop_no_conn_total 572822
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1223045
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7784
telemt_desync_full_logged_total 2310
telemt_desync_suppressed_total 5474
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 2970
telemt_desync_frames_bucket_total{bucket="gt_10"} 2742
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17837
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17025
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 790
telemt_user_connections_total{user="hello"} 1217257
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 24699658447 (23.00 GB)
telemt_user_octets_to_client{user="hello"} 431007843135 (401.41 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 115648.0 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1401612
telemt_connections_bad_total 64256
telemt_handshake_timeouts_total 47329
telemt_upstream_connect_attempt_total 468653
telemt_upstream_connect_success_total 467068
telemt_upstream_connect_fail_total 1585
telemt_upstream_connect_attempts_per_request{bucket="1"} 468653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33591
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1585
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123821
telemt_me_reconnect_success_total 18380
telemt_me_reader_eof_total 20554
telemt_me_idle_close_by_peer_total 20541
telemt_me_route_drop_no_conn_total 361418
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777068
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3638
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 2389
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 1519
telemt_desync_frames_bucket_total{bucket="gt_10"} 1404
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19947
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 18362
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1567
telemt_user_connections_total{user="hello"} 1219413
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 16426869713 (15.30 GB)
telemt_user_octets_to_client{user="hello"} 429492268706 (400.00 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 115423.8 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850404
telemt_connections_bad_total 59523
telemt_handshake_timeouts_total 24721
telemt_upstream_connect_attempt_total 26949
telemt_upstream_connect_success_total 26793
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 26949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41678
telemt_me_reconnect_success_total 20984
telemt_me_reader_eof_total 22831
telemt_me_idle_close_by_peer_total 22824
telemt_me_route_drop_no_conn_total 334263
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715260
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2243
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1515
telemt_desync_frames_bucket_total{bucket="1_2"} 641
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 21912
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20972
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 713376
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 44126717268 (41.10 GB)
telemt_user_octets_to_client{user="hello"} 318554255592 (296.68 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 115483.3 (32h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1327879
telemt_connections_bad_total 60607
telemt_handshake_timeouts_total 22338
telemt_upstream_connect_attempt_total 89741
telemt_upstream_connect_success_total 87319
telemt_upstream_connect_fail_total 2422
telemt_upstream_connect_attempts_per_request{bucket="1"} 89741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2422
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37191
telemt_me_reconnect_success_total 16787
telemt_me_reader_eof_total 18474
telemt_me_idle_close_by_peer_total 18471
telemt_me_route_drop_no_conn_total 544614
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078582
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4002
telemt_desync_full_logged_total 1324
telemt_desync_suppressed_total 2678
telemt_desync_frames_bucket_total{bucket="1_2"} 977
telemt_desync_frames_bucket_total{bucket="3_10"} 1677
telemt_desync_frames_bucket_total{bucket="gt_10"} 1348
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17740
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16767
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 953
telemt_user_connections_total{user="hello"} 1141956
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 17861459358 (16.63 GB)
telemt_user_octets_to_client{user="hello"} 541614288198 (504.42 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 115455.4 (32h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 887469
telemt_connections_bad_total 101086
telemt_handshake_timeouts_total 6963
telemt_upstream_connect_attempt_total 46560
telemt_upstream_connect_success_total 45922
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 46560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58636
telemt_me_reconnect_success_total 23673
telemt_me_reader_eof_total 25651
telemt_me_idle_close_by_peer_total 25648
telemt_me_route_drop_no_conn_total 282804
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717498
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3297
telemt_desync_full_logged_total 989
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1316
telemt_desync_frames_bucket_total{bucket="gt_10"} 952
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25140
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23665
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1467
telemt_user_connections_total{user="hello"} 734052
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 14000250412 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 361383885252 (336.56 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 115616.1 (32h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1135099
telemt_connections_bad_total 124863
telemt_handshake_timeouts_total 9912
telemt_upstream_connect_attempt_total 23014
telemt_upstream_connect_success_total 22883
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 23014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28413
telemt_me_reconnect_success_total 17123
telemt_me_reader_eof_total 18568
telemt_me_idle_close_by_peer_total 18566
telemt_me_route_drop_no_conn_total 783772
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110147
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
telemt_pool_swap_total 103
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17745
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17109
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 929158
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 14964530816 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 406635672292 (378.71 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 63383.5 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436421
telemt_connections_bad_total 44797
telemt_handshake_timeouts_total 11620
telemt_upstream_connect_attempt_total 23265
telemt_upstream_connect_success_total 23036
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 23265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31324
telemt_me_reconnect_success_total 19716
telemt_me_reader_eof_total 20850
telemt_me_idle_close_by_peer_total 20850
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 107447
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316000
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1383
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 939
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 528
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20296
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19677
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 315936
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 22689992697 (21.13 GB)
telemt_user_octets_to_client{user="hello"} 264698486150 (246.52 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 45
```