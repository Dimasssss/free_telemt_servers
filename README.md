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

# Server Metrics 2026-03-14 01:31:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 151101.2 (41h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596862
telemt_connections_bad_total 21865
telemt_handshake_timeouts_total 12874
telemt_upstream_connect_attempt_total 38542
telemt_upstream_connect_success_total 38352
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 38542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5498
telemt_me_reconnect_attempts_total 35110
telemt_me_reconnect_success_total 30435
telemt_me_reader_eof_total 32504
telemt_me_idle_close_by_peer_total 32503
telemt_me_route_drop_no_conn_total 195773
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511128
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 30917
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30419
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 511023
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 15567624506 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 252000840272 (234.69 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 150993.9 (41h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305839
telemt_connections_bad_total 2236
telemt_handshake_timeouts_total 1939
telemt_upstream_connect_attempt_total 143029
telemt_upstream_connect_success_total 141920
telemt_upstream_connect_fail_total 1109
telemt_upstream_connect_attempts_per_request{bucket="1"} 143029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1109
telemt_me_keepalive_timeout_total 3790
telemt_me_reconnect_attempts_total 162026
telemt_me_reconnect_success_total 31079
telemt_me_reader_eof_total 35975
telemt_me_idle_close_by_peer_total 35975
telemt_me_route_drop_no_conn_total 96435
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186842
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 35463
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 31062
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4384
telemt_user_connections_total{user="hello"} 289954
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 3033107399 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90511842735 (84.30 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 150958.0 (41h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358181
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 33212
telemt_upstream_connect_attempt_total 40042
telemt_upstream_connect_success_total 40036
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 40042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3283
telemt_me_reconnect_attempts_total 33736
telemt_me_reconnect_success_total 32472
telemt_me_reader_eof_total 34889
telemt_me_idle_close_by_peer_total 34889
telemt_me_route_drop_no_conn_total 127209
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309655
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 32857
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32452
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 309545
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 12612109404 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 126995403932 (118.27 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 150933.2 (41h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459388
telemt_connections_bad_total 15368
telemt_handshake_timeouts_total 4322
telemt_upstream_connect_attempt_total 68568
telemt_upstream_connect_success_total 58119
telemt_upstream_connect_fail_total 10449
telemt_upstream_connect_attempts_per_request{bucket="1"} 68568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 320
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10449
telemt_me_keepalive_timeout_total 5080
telemt_me_reconnect_attempts_total 136545
telemt_me_reconnect_success_total 31567
telemt_me_reader_eof_total 35756
telemt_me_idle_close_by_peer_total 35748
telemt_me_route_drop_no_conn_total 162184
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389319
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 35226
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 31557
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3659
telemt_user_connections_total{user="hello"} 408161
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 9064477019 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 156075806508 (145.36 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 101104.7 (28h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168690
telemt_connections_bad_total 24628
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 37106
telemt_upstream_connect_success_total 36765
telemt_upstream_connect_fail_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 37106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 341
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 40232
telemt_me_reconnect_success_total 26819
telemt_me_reader_eof_total 28688
telemt_me_idle_close_by_peer_total 28688
telemt_me_route_drop_no_conn_total 50274
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132727
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 27481
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26801
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 662
telemt_user_connections_total{user="hello"} 137535
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 1868195009 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 64270025747 (59.86 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 150889.1 (41h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880033
telemt_connections_bad_total 27482
telemt_handshake_timeouts_total 25323
telemt_upstream_connect_attempt_total 31188
telemt_upstream_connect_success_total 31021
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 3482
telemt_me_reconnect_attempts_total 28212
telemt_me_reconnect_success_total 23547
telemt_me_reader_eof_total 25221
telemt_me_idle_close_by_peer_total 25218
telemt_me_route_drop_no_conn_total 418980
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822416
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 23998
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23540
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 795172
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 14127562508 (13.16 GB)
telemt_user_octets_to_client{user="hello"} 405553574888 (377.70 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 34
```