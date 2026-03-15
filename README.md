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

# Server Metrics 2026-03-15 12:30:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 51354.3 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224347
telemt_connections_bad_total 1736
telemt_handshake_timeouts_total 4681
telemt_upstream_connect_attempt_total 13039
telemt_upstream_connect_success_total 12969
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13766
telemt_me_reconnect_success_total 10394
telemt_me_reader_eof_total 11099
telemt_me_idle_close_by_peer_total 11099
telemt_me_route_drop_no_conn_total 425967
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270414
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1554
telemt_desync_full_logged_total 615
telemt_desync_suppressed_total 939
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10604
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10363
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 209525
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 4117855992 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 195002774388 (181.61 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 51360.6 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79752
telemt_connections_bad_total 2692
telemt_handshake_timeouts_total 6122
telemt_upstream_connect_attempt_total 13984
telemt_upstream_connect_success_total 13983
telemt_upstream_connect_attempts_per_request{bucket="1"} 13983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13727
telemt_me_reconnect_success_total 11390
telemt_me_reader_eof_total 12197
telemt_me_idle_close_by_peer_total 12197
telemt_me_route_drop_no_conn_total 35483
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68419
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11586
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11374
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 68417
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 1396025848 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 31314450976 (29.16 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 51353.1 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83169
telemt_connections_bad_total 1034
telemt_handshake_timeouts_total 2592
telemt_upstream_connect_attempt_total 15008
telemt_upstream_connect_success_total 15000
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14547
telemt_me_reconnect_success_total 12402
telemt_me_reader_eof_total 13243
telemt_me_idle_close_by_peer_total 13243
telemt_me_route_drop_no_conn_total 32111
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75892
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12586
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12394
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 75806
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 9561217104 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 45220321436 (42.11 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 51352.9 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113311
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 721
telemt_upstream_connect_attempt_total 12072
telemt_upstream_connect_success_total 12071
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9555
telemt_me_reconnect_success_total 9503
telemt_me_reader_eof_total 10131
telemt_me_idle_close_by_peer_total 10131
telemt_me_route_drop_no_conn_total 45192
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103413
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9610
telemt_me_writer_restored_same_endpoint_total 9492
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 103333
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 1820784508 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 56488588308 (52.61 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 26424.3 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61016
telemt_connections_bad_total 15876
telemt_handshake_timeouts_total 874
telemt_upstream_connect_attempt_total 8539
telemt_upstream_connect_success_total 8479
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 101382
telemt_me_reconnect_success_total 6962
telemt_me_reader_eof_total 7263
telemt_me_idle_close_by_peer_total 7263
telemt_me_route_drop_no_conn_total 21284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42896
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6955
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6858
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 43032
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 662072925 (631.40 MB)
telemt_user_octets_to_client{user="hello"} 17056753571 (15.89 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 51352.5 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295472
telemt_connections_bad_total 47711
telemt_handshake_timeouts_total 2159
telemt_upstream_connect_attempt_total 10883
telemt_upstream_connect_success_total 10817
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 8293
telemt_me_reconnect_success_total 8237
telemt_me_reader_eof_total 8763
telemt_me_idle_close_by_peer_total 8763
telemt_me_route_drop_no_conn_total 131744
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236900
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8309
telemt_me_writer_restored_same_endpoint_total 8210
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 235260
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 4990484448 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 114610016368 (106.74 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 80
```