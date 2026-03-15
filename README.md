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

# Server Metrics 2026-03-15 01:54:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 13191.4 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27812
telemt_connections_bad_total 368
telemt_handshake_timeouts_total 274
telemt_upstream_connect_attempt_total 3366
telemt_upstream_connect_success_total 3345
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2678
telemt_me_reconnect_success_total 2665
telemt_me_reader_eof_total 2821
telemt_me_idle_close_by_peer_total 2821
telemt_me_route_drop_no_conn_total 7987
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26333
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2672
telemt_me_writer_restored_same_endpoint_total 2634
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 26331
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 285215212 (272.00 MB)
telemt_user_octets_to_client{user="hello"} 10272858180 (9.57 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 13197.8 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12433
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 3664
telemt_upstream_connect_success_total 3664
telemt_upstream_connect_attempts_per_request{bucket="1"} 3664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2992
telemt_me_reconnect_success_total 2981
telemt_me_reader_eof_total 3173
telemt_me_idle_close_by_peer_total 3173
telemt_me_route_drop_no_conn_total 4537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11745
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2998
telemt_me_writer_restored_same_endpoint_total 2965
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 11749
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 398239340 (379.79 MB)
telemt_user_octets_to_client{user="hello"} 2051319600 (1.91 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 13190.5 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12655
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 3530
telemt_upstream_connect_success_total 3529
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2861
telemt_me_reconnect_success_total 2847
telemt_me_reader_eof_total 3062
telemt_me_idle_close_by_peer_total 3062
telemt_me_route_drop_no_conn_total 4363
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11892
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2866
telemt_me_writer_restored_same_endpoint_total 2843
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 11851
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 8607708232 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 13445001380 (12.52 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 13190.3 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13699
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 3190
telemt_upstream_connect_success_total 3189
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2525
telemt_me_reconnect_success_total 2513
telemt_me_reader_eof_total 2666
telemt_me_idle_close_by_peer_total 2666
telemt_me_route_drop_no_conn_total 5317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13010
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2533
telemt_me_writer_restored_same_endpoint_total 2502
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 13008
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 371566684 (354.35 MB)
telemt_user_octets_to_client{user="hello"} 9874493704 (9.20 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 13190.4 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16206
telemt_connections_bad_total 2665
telemt_handshake_timeouts_total 388
telemt_upstream_connect_attempt_total 4256
telemt_upstream_connect_success_total 4203
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 3603
telemt_me_reconnect_success_total 3524
telemt_me_reader_eof_total 3708
telemt_me_idle_close_by_peer_total 3708
telemt_me_route_drop_no_conn_total 4678
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12844
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3535
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3512
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 12830
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 183759344 (175.25 MB)
telemt_user_octets_to_client{user="hello"} 6843413604 (6.37 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 13189.4 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41789
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 2886
telemt_upstream_connect_success_total 2868
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2199
telemt_me_reconnect_success_total 2191
telemt_me_reader_eof_total 2302
telemt_me_idle_close_by_peer_total 2302
telemt_me_route_drop_no_conn_total 23221
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40903
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2184
telemt_me_writer_restored_same_endpoint_total 2164
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 39472
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1478210608 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 25874073480 (24.10 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 33
```