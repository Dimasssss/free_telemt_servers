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

# Server Metrics 2026-03-14 15:37:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 8445.2 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48071
telemt_connections_bad_total 8258
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 2212
telemt_upstream_connect_success_total 2210
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 1747
telemt_me_reconnect_success_total 1724
telemt_me_reader_eof_total 1798
telemt_me_idle_close_by_peer_total 1798
telemt_me_route_drop_no_conn_total 18628
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38396
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1759
telemt_me_writer_restored_same_endpoint_total 1706
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 38332
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 677346916 (645.97 MB)
telemt_user_octets_to_client{user="hello"} 13694913368 (12.75 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 8443.7 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19276
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 2386
telemt_upstream_connect_success_total 2359
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 4438
telemt_me_reconnect_success_total 1881
telemt_me_reader_eof_total 2015
telemt_me_idle_close_by_peer_total 2015
telemt_me_route_drop_no_conn_total 10131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18083
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1988
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1876
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 18066
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 244270312 (232.95 MB)
telemt_user_octets_to_client{user="hello"} 6942952660 (6.47 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 8447.7 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19000
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 722
telemt_upstream_connect_attempt_total 3717
telemt_upstream_connect_success_total 3684
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 3717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 96766
telemt_me_reconnect_success_total 2887
telemt_me_reader_eof_total 3024
telemt_me_idle_close_by_peer_total 3024
telemt_me_route_drop_no_conn_total 7583
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16757
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3010
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2849
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 17050
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 529966141 (505.42 MB)
telemt_user_octets_to_client{user="hello"} 7988125550 (7.44 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 8452.7 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27031
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 182
telemt_upstream_connect_attempt_total 2379
telemt_upstream_connect_success_total 2364
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 1899
telemt_me_reconnect_success_total 1886
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1947
telemt_me_route_drop_no_conn_total 12930
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25687
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1897
telemt_me_writer_restored_same_endpoint_total 1884
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 25569
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 298069716 (284.26 MB)
telemt_user_octets_to_client{user="hello"} 10006526724 (9.32 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 8445.7 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18317
telemt_connections_bad_total 1706
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 1884
telemt_upstream_connect_success_total 1855
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 1884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1093
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 7882
telemt_me_reconnect_success_total 1374
telemt_me_reader_eof_total 1569
telemt_me_idle_close_by_peer_total 1569
telemt_me_route_drop_no_conn_total 6679
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15482
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1577
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1370
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 15478
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 123234836 (117.53 MB)
telemt_user_octets_to_client{user="hello"} 3844044088 (3.58 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 8445.5 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66162
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 465
telemt_upstream_connect_attempt_total 1941
telemt_upstream_connect_success_total 1900
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 2438
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1467
telemt_me_idle_close_by_peer_total 1467
telemt_me_route_drop_no_conn_total 33490
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61338
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1458
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 1411
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 61242
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 1032051108 (984.24 MB)
telemt_user_octets_to_client{user="hello"} 23708944296 (22.08 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 59
```