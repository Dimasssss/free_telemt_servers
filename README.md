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

# Server Metrics 2026-03-13 12:52:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 105561.5 (29h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432677
telemt_connections_bad_total 3212
telemt_handshake_timeouts_total 8421
telemt_upstream_connect_attempt_total 26779
telemt_upstream_connect_success_total 26652
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 26779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2396
telemt_me_reconnect_attempts_total 24873
telemt_me_reconnect_success_total 21348
telemt_me_reader_eof_total 22795
telemt_me_idle_close_by_peer_total 22794
telemt_me_route_drop_no_conn_total 137069
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376558
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1284
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 21679
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21332
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 376149
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 6758518880 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 163030298576 (151.83 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 105455.4 (29h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200113
telemt_connections_bad_total 1659
telemt_handshake_timeouts_total 1489
telemt_upstream_connect_attempt_total 61252
telemt_upstream_connect_success_total 60539
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 61252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 587
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 1369
telemt_me_reconnect_attempts_total 99035
telemt_me_reconnect_success_total 25970
telemt_me_reader_eof_total 29013
telemt_me_idle_close_by_peer_total 29013
telemt_me_route_drop_no_conn_total 79278
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159760
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28477
telemt_me_refill_failed_total 2279
telemt_me_writer_restored_same_endpoint_total 25953
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2507
telemt_user_connections_total{user="hello"} 188819
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 1922020981 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 62071373762 (57.81 GB)
telemt_user_msgs_from_client{user="hello"} 440293
telemt_user_msgs_to_client{user="hello"} 3141766
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 105419.1 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243444
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 8472
telemt_upstream_connect_attempt_total 28531
telemt_upstream_connect_success_total 28527
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2207
telemt_me_reconnect_attempts_total 24397
telemt_me_reconnect_success_total 23185
telemt_me_reader_eof_total 24835
telemt_me_idle_close_by_peer_total 24835
telemt_me_route_drop_no_conn_total 90081
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224059
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 23439
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23165
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 223972
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9399816228 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 98404705488 (91.65 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 105394.3 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339429
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 2498
telemt_upstream_connect_attempt_total 40293
telemt_upstream_connect_success_total 30201
telemt_upstream_connect_fail_total 10092
telemt_upstream_connect_attempts_per_request{bucket="1"} 40293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10092
telemt_me_keepalive_timeout_total 4081
telemt_me_reconnect_attempts_total 93432
telemt_me_reconnect_success_total 21879
telemt_me_reader_eof_total 24779
telemt_me_idle_close_by_peer_total 24772
telemt_me_route_drop_no_conn_total 122256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292527
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1042
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24387
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21869
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2508
telemt_user_connections_total{user="hello"} 295438
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 5989145070 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 111151259149 (103.52 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 55566.0 (15h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81586
telemt_connections_bad_total 10951
telemt_handshake_timeouts_total 1186
telemt_upstream_connect_attempt_total 23786
telemt_upstream_connect_success_total 23598
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 23786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 25822
telemt_me_reconnect_success_total 15904
telemt_me_reader_eof_total 17072
telemt_me_idle_close_by_peer_total 17072
telemt_me_route_drop_no_conn_total 24168
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61925
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 16353
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15886
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 66834
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 581984393 (555.02 MB)
telemt_user_octets_to_client{user="hello"} 18371353627 (17.11 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 105351.1 (29h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 605451
telemt_connections_bad_total 17828
telemt_handshake_timeouts_total 15471
telemt_upstream_connect_attempt_total 22322
telemt_upstream_connect_success_total 22207
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2503
telemt_me_reconnect_attempts_total 21584
telemt_me_reconnect_success_total 16962
telemt_me_reader_eof_total 18204
telemt_me_idle_close_by_peer_total 18201
telemt_me_route_drop_no_conn_total 297247
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578574
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17325
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16955
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 551623
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 9779532288 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 292084151176 (272.02 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 63
```