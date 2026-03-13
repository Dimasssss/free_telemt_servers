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

# Server Metrics 2026-03-13 07:59:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87942.7 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339039
telemt_connections_bad_total 3169
telemt_handshake_timeouts_total 7499
telemt_upstream_connect_attempt_total 22055
telemt_upstream_connect_success_total 21954
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 22055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1658
telemt_me_reconnect_attempts_total 21054
telemt_me_reconnect_success_total 17549
telemt_me_reader_eof_total 18769
telemt_me_idle_close_by_peer_total 18768
telemt_me_route_drop_no_conn_total 106044
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288755
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 962
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 17844
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17533
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 288448
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 4774465944 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 133434270836 (124.27 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 87835.5 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154492
telemt_connections_bad_total 1481
telemt_handshake_timeouts_total 1184
telemt_upstream_connect_attempt_total 44912
telemt_upstream_connect_success_total 44304
telemt_upstream_connect_fail_total 608
telemt_upstream_connect_attempts_per_request{bucket="1"} 44912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 608
telemt_me_keepalive_timeout_total 676
telemt_me_reconnect_attempts_total 77415
telemt_me_reconnect_success_total 23420
telemt_me_reader_eof_total 25799
telemt_me_idle_close_by_peer_total 25799
telemt_me_route_drop_no_conn_total 58252
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129507
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
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
telemt_me_writer_removed_unexpected_total 25298
telemt_me_refill_failed_total 1685
telemt_me_writer_restored_same_endpoint_total 23405
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1878
telemt_user_connections_total{user="hello"} 145999
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1513071168 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 46570095683 (43.37 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 87799.5 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186460
telemt_connections_bad_total 1975
telemt_handshake_timeouts_total 3090
telemt_upstream_connect_attempt_total 23847
telemt_upstream_connect_success_total 23845
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 569
telemt_me_reconnect_attempts_total 20598
telemt_me_reconnect_success_total 19419
telemt_me_reader_eof_total 20827
telemt_me_idle_close_by_peer_total 20827
telemt_me_route_drop_no_conn_total 72073
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174486
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
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 19631
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19399
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 174416
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 5962552676 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 74760781528 (69.63 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 87774.7 (24h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270863
telemt_connections_bad_total 13643
telemt_handshake_timeouts_total 2027
telemt_upstream_connect_attempt_total 36559
telemt_upstream_connect_success_total 26606
telemt_upstream_connect_fail_total 9953
telemt_upstream_connect_attempts_per_request{bucket="1"} 36559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9953
telemt_me_keepalive_timeout_total 3374
telemt_me_reconnect_attempts_total 70904
telemt_me_reconnect_success_total 19360
telemt_me_reader_eof_total 21597
telemt_me_idle_close_by_peer_total 21590
telemt_me_route_drop_no_conn_total 97208
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229720
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 831
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21219
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19350
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1859
telemt_user_connections_total{user="hello"} 232448
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 5241532822 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 88352906613 (82.29 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37946.3 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46840
telemt_connections_bad_total 7755
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 12879
telemt_upstream_connect_success_total 12745
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 12879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 304
telemt_me_reconnect_attempts_total 11793
telemt_me_reconnect_success_total 10824
telemt_me_reader_eof_total 11538
telemt_me_idle_close_by_peer_total 11538
telemt_me_route_drop_no_conn_total 13650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37376
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
telemt_me_writer_removed_unexpected_total 10948
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10806
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 37375
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 269636096 (257.15 MB)
telemt_user_octets_to_client{user="hello"} 11126225768 (10.36 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 87731.2 (24h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462460
telemt_connections_bad_total 13233
telemt_handshake_timeouts_total 3803
telemt_upstream_connect_attempt_total 18590
telemt_upstream_connect_success_total 18489
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1523
telemt_me_reconnect_attempts_total 17767
telemt_me_reconnect_success_total 14126
telemt_me_reader_eof_total 15174
telemt_me_idle_close_by_peer_total 15171
telemt_me_route_drop_no_conn_total 225057
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449397
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 372
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 14419
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14119
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 429215
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 7934517284 (7.39 GB)
telemt_user_octets_to_client{user="hello"} 247665654228 (230.66 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 50
```