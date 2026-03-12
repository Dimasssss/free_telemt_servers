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

# Server Metrics 2026-03-12 23:17:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 56621.6 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249358
telemt_connections_bad_total 2720
telemt_handshake_timeouts_total 5254
telemt_upstream_connect_attempt_total 14216
telemt_upstream_connect_success_total 14154
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1480
telemt_me_reconnect_attempts_total 14770
telemt_me_reconnect_success_total 11300
telemt_me_reader_eof_total 12037
telemt_me_idle_close_by_peer_total 12036
telemt_me_route_drop_no_conn_total 77260
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205718
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 433
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11536
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11284
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 205484
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 3825304920 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 105242733960 (98.01 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 56514.6 (15h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113592
telemt_connections_bad_total 569
telemt_handshake_timeouts_total 836
telemt_upstream_connect_attempt_total 32855
telemt_upstream_connect_success_total 32487
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 32854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 55019
telemt_me_reconnect_success_total 13148
telemt_me_reader_eof_total 14781
telemt_me_idle_close_by_peer_total 14781
telemt_me_route_drop_no_conn_total 41232
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 14551
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13133
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1403
telemt_user_connections_total{user="hello"} 107964
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1202402724 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 33951218579 (31.62 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 56478.2 (15h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138851
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 2224
telemt_upstream_connect_attempt_total 15532
telemt_upstream_connect_success_total 15531
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 13798
telemt_me_reconnect_success_total 12650
telemt_me_reader_eof_total 13496
telemt_me_idle_close_by_peer_total 13496
telemt_me_route_drop_no_conn_total 52247
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129728
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12809
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12630
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 129694
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 2583860660 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 60521185132 (56.36 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 56453.9 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202541
telemt_connections_bad_total 13262
telemt_handshake_timeouts_total 1372
telemt_upstream_connect_attempt_total 26987
telemt_upstream_connect_success_total 17287
telemt_upstream_connect_fail_total 9700
telemt_upstream_connect_attempts_per_request{bucket="1"} 26987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9700
telemt_me_keepalive_timeout_total 2494
telemt_me_reconnect_attempts_total 43829
telemt_me_reconnect_success_total 11582
telemt_me_reader_eof_total 13019
telemt_me_idle_close_by_peer_total 13012
telemt_me_route_drop_no_conn_total 71436
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166593
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12765
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 11572
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1183
telemt_user_connections_total{user="hello"} 169347
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2982013770 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 68929674897 (64.20 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6625.5 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6226
telemt_connections_bad_total 1223
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 1959
telemt_upstream_connect_success_total 1937
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1568
telemt_me_reconnect_success_total 1567
telemt_me_reader_eof_total 1664
telemt_me_idle_close_by_peer_total 1664
telemt_me_route_drop_no_conn_total 1692
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4779
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1574
telemt_me_writer_restored_same_endpoint_total 1551
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 4779
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 13318384 (12.70 MB)
telemt_user_octets_to_client{user="hello"} 1339891344 (1.25 GB)
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 56410.4 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331399
telemt_connections_bad_total 5143
telemt_handshake_timeouts_total 2528
telemt_upstream_connect_attempt_total 11844
telemt_upstream_connect_success_total 11778
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 11844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 12568
telemt_me_reconnect_success_total 8955
telemt_me_reader_eof_total 9575
telemt_me_idle_close_by_peer_total 9574
telemt_me_route_drop_no_conn_total 149149
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325755
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9177
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8948
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 314058
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 5483897988 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 167570015396 (156.06 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 29
```