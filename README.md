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

# Server Metrics 2026-03-13 01:35:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 64908.9 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264474
telemt_connections_bad_total 2773
telemt_handshake_timeouts_total 5614
telemt_upstream_connect_attempt_total 16420
telemt_upstream_connect_success_total 16349
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1510
telemt_me_reconnect_attempts_total 16531
telemt_me_reconnect_success_total 13055
telemt_me_reader_eof_total 13930
telemt_me_idle_close_by_peer_total 13929
telemt_me_route_drop_no_conn_total 82280
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219320
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13304
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13039
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 219088
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 3950901680 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 109847977108 (102.30 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 64801.7 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122999
telemt_connections_bad_total 733
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 36171
telemt_upstream_connect_success_total 35730
telemt_upstream_connect_fail_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 36171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 441
telemt_me_keepalive_timeout_total 462
telemt_me_reconnect_attempts_total 60208
telemt_me_reconnect_success_total 15995
telemt_me_reader_eof_total 17801
telemt_me_idle_close_by_peer_total 17801
telemt_me_route_drop_no_conn_total 43897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100244
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 17493
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 15980
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1498
telemt_user_connections_total{user="hello"} 116744
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 1249699660 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 35270114119 (32.85 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 64765.5 (17h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148331
telemt_connections_bad_total 1700
telemt_handshake_timeouts_total 2346
telemt_upstream_connect_attempt_total 17839
telemt_upstream_connect_success_total 17836
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 367
telemt_me_reconnect_attempts_total 15718
telemt_me_reconnect_success_total 14561
telemt_me_reader_eof_total 15561
telemt_me_idle_close_by_peer_total 15561
telemt_me_route_drop_no_conn_total 56455
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138714
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
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 14726
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14541
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 138678
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 2640267752 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 63794712596 (59.41 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 64741.2 (17h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211855
telemt_connections_bad_total 13302
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 29889
telemt_upstream_connect_success_total 20121
telemt_upstream_connect_fail_total 9768
telemt_upstream_connect_attempts_per_request{bucket="1"} 29889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9768
telemt_me_keepalive_timeout_total 3216
telemt_me_reconnect_attempts_total 50918
telemt_me_reconnect_success_total 14020
telemt_me_reader_eof_total 15670
telemt_me_idle_close_by_peer_total 15663
telemt_me_route_drop_no_conn_total 76255
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175558
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15378
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 14010
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1358
telemt_user_connections_total{user="hello"} 178310
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 3037710686 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 73175452089 (68.15 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14912.8 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13245
telemt_connections_bad_total 2819
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 4654
telemt_upstream_connect_success_total 4614
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 4654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3858
telemt_me_reconnect_success_total 3848
telemt_me_reader_eof_total 4112
telemt_me_idle_close_by_peer_total 4112
telemt_me_route_drop_no_conn_total 4117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10006
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3871
telemt_me_writer_restored_same_endpoint_total 3832
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 10006
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 45005864 (42.92 MB)
telemt_user_octets_to_client{user="hello"} 2850041252 (2.65 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 64697.5 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355697
telemt_connections_bad_total 6570
telemt_handshake_timeouts_total 2610
telemt_upstream_connect_attempt_total 13697
telemt_upstream_connect_success_total 13624
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 13697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 1342
telemt_me_reconnect_attempts_total 14027
telemt_me_reconnect_success_total 10409
telemt_me_reader_eof_total 11168
telemt_me_idle_close_by_peer_total 11166
telemt_me_route_drop_no_conn_total 158930
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347970
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10649
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10402
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 336271
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 5699477264 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 182158654576 (169.65 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 24
```