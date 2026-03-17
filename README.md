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

# Server Metrics 2026-03-17 16:57:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 79920.7 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940913
telemt_connections_bad_total 6494
telemt_handshake_timeouts_total 26340
telemt_upstream_connect_attempt_total 18926
telemt_upstream_connect_success_total 18452
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 18926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29265
telemt_me_reconnect_success_total 12150
telemt_me_reader_eof_total 13263
telemt_me_idle_close_by_peer_total 13262
telemt_me_route_drop_no_conn_total 435672
telemt_me_route_drop_channel_closed_total 116
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 864816
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5801
telemt_desync_full_logged_total 1624
telemt_desync_suppressed_total 4177
telemt_desync_frames_bucket_total{bucket="1_2"} 1626
telemt_desync_frames_bucket_total{bucket="3_10"} 2252
telemt_desync_frames_bucket_total{bucket="gt_10"} 1923
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12853
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12128
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 859092
telemt_user_connections_current{user="hello"} 1236
telemt_user_octets_from_client{user="hello"} 13332390911 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 287827932843 (268.06 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 80173.0 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712883
telemt_connections_bad_total 41088
telemt_handshake_timeouts_total 29524
telemt_upstream_connect_attempt_total 238322
telemt_upstream_connect_success_total 237658
telemt_upstream_connect_fail_total 660
telemt_upstream_connect_attempts_per_request{bucket="1"} 238318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 196675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20873
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 660
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 47079
telemt_me_reconnect_success_total 13562
telemt_me_reader_eof_total 15161
telemt_me_idle_close_by_peer_total 15161
telemt_me_route_drop_no_conn_total 207967
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1507
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1033
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14772
telemt_me_refill_failed_total 1043
telemt_me_writer_restored_same_endpoint_total 13546
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1210
telemt_user_connections_total{user="hello"} 610145
telemt_user_connections_current{user="hello"} 2569
telemt_user_octets_from_client{user="hello"} 7557989966 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 166880152960 (155.42 GB)
telemt_user_msgs_from_client{user="hello"} 3452307
telemt_user_msgs_to_client{user="hello"} 14419772
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 79948.4 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359685
telemt_connections_bad_total 9730
telemt_handshake_timeouts_total 20105
telemt_upstream_connect_attempt_total 20225
telemt_upstream_connect_success_total 20114
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 36725
telemt_me_reconnect_success_total 16059
telemt_me_reader_eof_total 17575
telemt_me_idle_close_by_peer_total 17572
telemt_me_route_drop_no_conn_total 182402
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313496
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 927
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 645
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 16917
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16047
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 858
telemt_user_connections_total{user="hello"} 311662
telemt_user_connections_current{user="hello"} 1676
telemt_user_octets_from_client{user="hello"} 22395139740 (20.86 GB)
telemt_user_octets_to_client{user="hello"} 97051678428 (90.39 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 80007.3 (22h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796048
telemt_connections_bad_total 14262
telemt_handshake_timeouts_total 15544
telemt_upstream_connect_attempt_total 80016
telemt_upstream_connect_success_total 79624
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 80016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 32535
telemt_me_reconnect_success_total 12241
telemt_me_reader_eof_total 13530
telemt_me_idle_close_by_peer_total 13529
telemt_me_route_drop_no_conn_total 295052
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629547
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2040
telemt_desync_full_logged_total 677
telemt_desync_suppressed_total 1363
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13089
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12232
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 848
telemt_user_connections_total{user="hello"} 692689
telemt_user_connections_current{user="hello"} 2196
telemt_user_octets_from_client{user="hello"} 8569097339 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 217042001009 (202.14 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 468
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 79979.3 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395825
telemt_connections_bad_total 67466
telemt_handshake_timeouts_total 4139
telemt_upstream_connect_attempt_total 38299
telemt_upstream_connect_success_total 37803
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 38299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48596
telemt_me_reconnect_success_total 17304
telemt_me_reader_eof_total 18875
telemt_me_idle_close_by_peer_total 18873
telemt_me_route_drop_no_conn_total 110842
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290624
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1356
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 611
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18565
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17296
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1261
telemt_user_connections_total{user="hello"} 307350
telemt_user_connections_current{user="hello"} 2153
telemt_user_octets_from_client{user="hello"} 4449723992 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 127102487772 (118.37 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 80141.7 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802395
telemt_connections_bad_total 60219
telemt_handshake_timeouts_total 7545
telemt_upstream_connect_attempt_total 16120
telemt_upstream_connect_success_total 16032
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 16120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23279
telemt_me_reconnect_success_total 12012
telemt_me_reader_eof_total 13080
telemt_me_idle_close_by_peer_total 13078
telemt_me_route_drop_no_conn_total 599044
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825551
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1373
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 889
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 519
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12562
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 11998
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 693383
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 10027359072 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 308224745060 (287.06 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 27907.4 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68617
telemt_connections_bad_total 3621
telemt_handshake_timeouts_total 542
telemt_upstream_connect_attempt_total 13981
telemt_upstream_connect_success_total 13864
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23873
telemt_me_reconnect_success_total 12299
telemt_me_reader_eof_total 13023
telemt_me_idle_close_by_peer_total 13023
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 18889
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60697
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 12805
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12279
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 60691
telemt_user_connections_current{user="hello"} 1359
telemt_user_octets_from_client{user="hello"} 3141102337 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 67805892034 (63.15 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 148
```