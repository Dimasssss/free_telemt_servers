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

# Server Metrics 2026-03-15 13:41:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 55642.8 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248376
telemt_connections_bad_total 2296
telemt_handshake_timeouts_total 5486
telemt_upstream_connect_attempt_total 13971
telemt_upstream_connect_success_total 13897
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 13971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 14497
telemt_me_reconnect_success_total 11119
telemt_me_reader_eof_total 11875
telemt_me_idle_close_by_peer_total 11875
telemt_me_route_drop_no_conn_total 433748
telemt_me_route_drop_channel_closed_total 66
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292239
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1670
telemt_desync_full_logged_total 660
telemt_desync_suppressed_total 1010
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 655
telemt_desync_frames_bucket_total{bucket="gt_10"} 720
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11337
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11088
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 231345
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 5116276692 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 204794529136 (190.73 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 55649.0 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90902
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 8449
telemt_upstream_connect_attempt_total 15289
telemt_upstream_connect_success_total 15289
telemt_upstream_connect_attempts_per_request{bucket="1"} 15289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 14828
telemt_me_reconnect_success_total 12484
telemt_me_reader_eof_total 13356
telemt_me_idle_close_by_peer_total 13356
telemt_me_route_drop_no_conn_total 38684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76934
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12695
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12468
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 76928
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1520598284 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 37135802484 (34.59 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 55641.6 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93223
telemt_connections_bad_total 1611
telemt_handshake_timeouts_total 2737
telemt_upstream_connect_attempt_total 16381
telemt_upstream_connect_success_total 16372
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 16380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 15716
telemt_me_reconnect_success_total 13562
telemt_me_reader_eof_total 14478
telemt_me_idle_close_by_peer_total 14478
telemt_me_route_drop_no_conn_total 36385
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84913
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13760
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 13554
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 84819
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 10024747232 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 51575221576 (48.03 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 55641.2 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128933
telemt_connections_bad_total 552
telemt_handshake_timeouts_total 849
telemt_upstream_connect_attempt_total 13101
telemt_upstream_connect_success_total 13098
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10383
telemt_me_reconnect_success_total 10321
telemt_me_reader_eof_total 10997
telemt_me_idle_close_by_peer_total 10997
telemt_me_route_drop_no_conn_total 50214
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117442
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10438
telemt_me_writer_restored_same_endpoint_total 10310
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 117359
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 2190997444 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 60494517800 (56.34 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 30712.7 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74415
telemt_connections_bad_total 20795
telemt_handshake_timeouts_total 1395
telemt_upstream_connect_attempt_total 9768
telemt_upstream_connect_success_total 9703
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102387
telemt_me_reconnect_success_total 7962
telemt_me_reader_eof_total 8314
telemt_me_idle_close_by_peer_total 8314
telemt_me_route_drop_no_conn_total 24907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50574
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 7968
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7858
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 50710
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 777318469 (741.31 MB)
telemt_user_octets_to_client{user="hello"} 20381839059 (18.98 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 55640.6 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328954
telemt_connections_bad_total 47910
telemt_handshake_timeouts_total 2603
telemt_upstream_connect_attempt_total 11839
telemt_upstream_connect_success_total 11768
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 9042
telemt_me_reconnect_success_total 8979
telemt_me_reader_eof_total 9552
telemt_me_idle_close_by_peer_total 9552
telemt_me_route_drop_no_conn_total 150683
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269164
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 278
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9064
telemt_me_writer_restored_same_endpoint_total 8952
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 267027
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 6166409524 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 130720079768 (121.74 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 61
```