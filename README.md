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

# Server Metrics 2026-03-12 16:43:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33016.1 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173741
telemt_connections_bad_total 2041
telemt_handshake_timeouts_total 4865
telemt_upstream_connect_attempt_total 8181
telemt_upstream_connect_success_total 8151
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 8181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 7591
telemt_me_reconnect_success_total 6457
telemt_me_reader_eof_total 6816
telemt_me_idle_close_by_peer_total 6815
telemt_me_route_drop_no_conn_total 50789
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148399
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6555
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6441
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 148358
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 2528278836 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 59348436776 (55.27 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32909.1 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73240
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 623
telemt_upstream_connect_attempt_total 10496
telemt_upstream_connect_success_total 10281
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 10496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 31748
telemt_me_reconnect_success_total 8612
telemt_me_reader_eof_total 9502
telemt_me_idle_close_by_peer_total 9502
telemt_me_route_drop_no_conn_total 32000
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69542
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9400
telemt_me_refill_failed_total 722
telemt_me_writer_restored_same_endpoint_total 8597
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 788
telemt_user_connections_total{user="hello"} 69527
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 781961880 (745.74 MB)
telemt_user_octets_to_client{user="hello"} 19336021892 (18.01 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32872.4 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98958
telemt_connections_bad_total 1489
telemt_handshake_timeouts_total 2041
telemt_upstream_connect_attempt_total 9190
telemt_upstream_connect_success_total 9190
telemt_upstream_connect_attempts_per_request{bucket="1"} 9190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 7531
telemt_me_reconnect_success_total 7464
telemt_me_reader_eof_total 7899
telemt_me_idle_close_by_peer_total 7899
telemt_me_route_drop_no_conn_total 36562
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91353
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7531
telemt_me_writer_restored_same_endpoint_total 7444
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 91327
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 2250965840 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 46536868884 (43.34 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32848.2 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135671
telemt_connections_bad_total 13063
telemt_handshake_timeouts_total 1001
telemt_upstream_connect_attempt_total 7292
telemt_upstream_connect_success_total 7069
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 7292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 32099
telemt_me_reconnect_success_total 5389
telemt_me_reader_eof_total 6356
telemt_me_idle_close_by_peer_total 6356
telemt_me_route_drop_no_conn_total 48468
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114663
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6285
telemt_me_refill_failed_total 833
telemt_me_writer_restored_same_endpoint_total 5381
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 114543
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 2132683444 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 49555758320 (46.15 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32817.6 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80014
telemt_connections_bad_total 8711
telemt_handshake_timeouts_total 1126
telemt_upstream_connect_attempt_total 39689
telemt_upstream_connect_success_total 39284
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 39689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 45170
telemt_me_reconnect_success_total 3687
telemt_me_reader_eof_total 4978
telemt_me_idle_close_by_peer_total 4978
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5006
telemt_me_refill_failed_total 1299
telemt_me_writer_restored_same_endpoint_total 3670
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1319
telemt_user_connections_total{user="hello"} 68361
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 610018523 (581.76 MB)
telemt_user_octets_to_client{user="hello"} 20327825468 (18.93 GB)
telemt_user_msgs_from_client{user="hello"} 536946
telemt_user_msgs_to_client{user="hello"} 2052987
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32805.4 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207207
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 1664
telemt_upstream_connect_attempt_total 7026
telemt_upstream_connect_success_total 6991
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 399
telemt_me_reconnect_attempts_total 6380
telemt_me_reconnect_success_total 5312
telemt_me_reader_eof_total 5607
telemt_me_idle_close_by_peer_total 5606
telemt_me_route_drop_no_conn_total 83356
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199949
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5416
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5305
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 197805
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 3691234692 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 88526173388 (82.45 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 72
```