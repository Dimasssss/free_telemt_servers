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

# Server Metrics 2026-03-12 23:32:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 57542.2 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251076
telemt_connections_bad_total 2728
telemt_handshake_timeouts_total 5258
telemt_upstream_connect_attempt_total 14460
telemt_upstream_connect_success_total 14398
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1483
telemt_me_reconnect_attempts_total 14971
telemt_me_reconnect_success_total 11500
telemt_me_reader_eof_total 12252
telemt_me_idle_close_by_peer_total 12251
telemt_me_route_drop_no_conn_total 77825
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207366
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
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11737
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11484
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 207132
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 3838388996 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 106283657692 (98.98 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 57435.4 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114586
telemt_connections_bad_total 634
telemt_handshake_timeouts_total 898
telemt_upstream_connect_attempt_total 33223
telemt_upstream_connect_success_total 32847
telemt_upstream_connect_fail_total 376
telemt_upstream_connect_attempts_per_request{bucket="1"} 33223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 376
telemt_me_keepalive_timeout_total 410
telemt_me_reconnect_attempts_total 55335
telemt_me_reconnect_success_total 13464
telemt_me_reader_eof_total 15099
telemt_me_idle_close_by_peer_total 15099
telemt_me_route_drop_no_conn_total 41559
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92310
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
telemt_me_writer_removed_unexpected_total 14869
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13449
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1405
telemt_user_connections_total{user="hello"} 108812
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1205788492 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 34029467227 (31.69 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 57398.8 (15h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139868
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 2236
telemt_upstream_connect_attempt_total 15776
telemt_upstream_connect_success_total 15775
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 336
telemt_me_reconnect_attempts_total 13999
telemt_me_reconnect_success_total 12851
telemt_me_reader_eof_total 13716
telemt_me_idle_close_by_peer_total 13716
telemt_me_route_drop_no_conn_total 52738
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130703
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
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13011
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12831
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 130669
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2596588200 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 60595320944 (56.43 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 57374.6 (15h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203490
telemt_connections_bad_total 13275
telemt_handshake_timeouts_total 1380
telemt_upstream_connect_attempt_total 27232
telemt_upstream_connect_success_total 17528
telemt_upstream_connect_fail_total 9704
telemt_upstream_connect_attempts_per_request{bucket="1"} 27232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9704
telemt_me_keepalive_timeout_total 2500
telemt_me_reconnect_attempts_total 44026
telemt_me_reconnect_success_total 11778
telemt_me_reader_eof_total 13230
telemt_me_idle_close_by_peer_total 13223
telemt_me_route_drop_no_conn_total 71975
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167491
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12963
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 11768
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1185
telemt_user_connections_total{user="hello"} 170245
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2986097362 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 69520683993 (64.75 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7546.2 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6847
telemt_connections_bad_total 1388
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2301
telemt_upstream_connect_success_total 2274
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1862
telemt_me_reconnect_success_total 1859
telemt_me_reader_eof_total 1961
telemt_me_idle_close_by_peer_total 1961
telemt_me_route_drop_no_conn_total 1891
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5217
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1871
telemt_me_writer_restored_same_endpoint_total 1843
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 5217
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 15286604 (14.58 MB)
telemt_user_octets_to_client{user="hello"} 1579086072 (1.47 GB)
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 57331.1 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334480
telemt_connections_bad_total 5147
telemt_handshake_timeouts_total 2532
telemt_upstream_connect_attempt_total 12025
telemt_upstream_connect_success_total 11958
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 12705
telemt_me_reconnect_success_total 9091
telemt_me_reader_eof_total 9722
telemt_me_idle_close_by_peer_total 9721
telemt_me_route_drop_no_conn_total 150160
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328776
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
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9313
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9084
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 317079
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 5512120124 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 170417266420 (158.71 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 21
```