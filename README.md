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

# Server Metrics 2026-03-13 08:09:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 88556.8 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342394
telemt_connections_bad_total 3171
telemt_handshake_timeouts_total 7543
telemt_upstream_connect_attempt_total 22206
telemt_upstream_connect_success_total 22104
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 22206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1659
telemt_me_reconnect_attempts_total 21159
telemt_me_reconnect_success_total 17654
telemt_me_reader_eof_total 18885
telemt_me_idle_close_by_peer_total 18884
telemt_me_route_drop_no_conn_total 107068
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291982
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 969
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 610
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 17950
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17638
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 291673
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 4827089752 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 134523700528 (125.28 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 88450.6 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156023
telemt_connections_bad_total 1484
telemt_handshake_timeouts_total 1202
telemt_upstream_connect_attempt_total 45061
telemt_upstream_connect_success_total 44450
telemt_upstream_connect_fail_total 611
telemt_upstream_connect_attempts_per_request{bucket="1"} 45061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 611
telemt_me_keepalive_timeout_total 678
telemt_me_reconnect_attempts_total 78893
telemt_me_reconnect_success_total 23522
telemt_me_reader_eof_total 25944
telemt_me_idle_close_by_peer_total 25944
telemt_me_route_drop_no_conn_total 58820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130971
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 25443
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23507
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1921
telemt_user_connections_total{user="hello"} 147463
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 1533441712 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 47395635099 (44.14 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 88414.3 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188354
telemt_connections_bad_total 1983
telemt_handshake_timeouts_total 3099
telemt_upstream_connect_attempt_total 24004
telemt_upstream_connect_success_total 24002
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 24004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 20712
telemt_me_reconnect_success_total 19533
telemt_me_reader_eof_total 20954
telemt_me_idle_close_by_peer_total 20954
telemt_me_route_drop_no_conn_total 72645
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176321
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 19745
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19513
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 176251
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 6636235940 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 75098492720 (69.94 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 88389.8 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273357
telemt_connections_bad_total 13645
telemt_handshake_timeouts_total 2034
telemt_upstream_connect_attempt_total 36728
telemt_upstream_connect_success_total 26767
telemt_upstream_connect_fail_total 9961
telemt_upstream_connect_attempts_per_request{bucket="1"} 36728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9961
telemt_me_keepalive_timeout_total 3379
telemt_me_reconnect_attempts_total 71020
telemt_me_reconnect_success_total 19476
telemt_me_reader_eof_total 21714
telemt_me_idle_close_by_peer_total 21707
telemt_me_route_drop_no_conn_total 98322
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232018
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 858
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21336
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19466
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1860
telemt_user_connections_total{user="hello"} 234744
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 5252395166 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 88939399365 (82.83 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38561.5 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47935
telemt_connections_bad_total 7867
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 13159
telemt_upstream_connect_success_total 13025
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 13159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 12071
telemt_me_reconnect_success_total 11102
telemt_me_reader_eof_total 11817
telemt_me_idle_close_by_peer_total 11817
telemt_me_route_drop_no_conn_total 14224
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38338
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11227
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 11084
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 38337
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 274193896 (261.49 MB)
telemt_user_octets_to_client{user="hello"} 11238368376 (10.47 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 88346.5 (24h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467050
telemt_connections_bad_total 13314
telemt_handshake_timeouts_total 3943
telemt_upstream_connect_attempt_total 18714
telemt_upstream_connect_success_total 18613
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1525
telemt_me_reconnect_attempts_total 17848
telemt_me_reconnect_success_total 14207
telemt_me_reader_eof_total 15262
telemt_me_idle_close_by_peer_total 15259
telemt_me_route_drop_no_conn_total 230900
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454710
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 14501
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14200
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 433229
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 7979975624 (7.43 GB)
telemt_user_octets_to_client{user="hello"} 249760337464 (232.61 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 53
```