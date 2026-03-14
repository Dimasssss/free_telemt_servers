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

# Server Metrics 2026-03-14 23:16:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 3727.2 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7622
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 960
telemt_upstream_connect_success_total 954
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 718
telemt_me_reconnect_success_total 714
telemt_me_reader_eof_total 715
telemt_me_idle_close_by_peer_total 715
telemt_me_route_drop_no_conn_total 2041
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6849
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_restored_same_endpoint_total 683
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 6848
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 69458668 (66.24 MB)
telemt_user_octets_to_client{user="hello"} 1750365556 (1.63 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 3733.8 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2738
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1099
telemt_upstream_connect_success_total 1099
telemt_upstream_connect_attempts_per_request{bucket="1"} 1099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_me_reconnect_attempts_total 857
telemt_me_reconnect_success_total 855
telemt_me_reader_eof_total 876
telemt_me_idle_close_by_peer_total 876
telemt_me_route_drop_no_conn_total 998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2592
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 856
telemt_me_writer_restored_same_endpoint_total 839
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 2592
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 29256568 (27.90 MB)
telemt_user_octets_to_client{user="hello"} 438276216 (417.97 MB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 3726.5 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3638
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 61
telemt_upstream_connect_attempt_total 987
telemt_upstream_connect_success_total 986
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 748
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 774
telemt_me_idle_close_by_peer_total 774
telemt_me_route_drop_no_conn_total 1111
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3423
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 735
telemt_me_writer_restored_same_endpoint_total 736
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 3416
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 751697048 (716.87 MB)
telemt_user_octets_to_client{user="hello"} 7116735424 (6.63 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 3726.2 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3462
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 916
telemt_upstream_connect_success_total 916
telemt_upstream_connect_attempts_per_request{bucket="1"} 916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 681
telemt_me_reconnect_success_total 677
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 1585
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3345
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 674
telemt_me_writer_restored_same_endpoint_total 666
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 3345
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 64468324 (61.48 MB)
telemt_user_octets_to_client{user="hello"} 4438614048 (4.13 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 3726.2 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5004
telemt_connections_bad_total 928
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 1328
telemt_upstream_connect_success_total 1307
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1137
telemt_me_reconnect_success_total 1070
telemt_me_reader_eof_total 1071
telemt_me_idle_close_by_peer_total 1071
telemt_me_route_drop_no_conn_total 954
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3666
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1058
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1058
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 3661
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 43767152 (41.74 MB)
telemt_user_octets_to_client{user="hello"} 3512857404 (3.27 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 3725.4 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12233
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 889
telemt_upstream_connect_success_total 885
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 647
telemt_me_reconnect_success_total 645
telemt_me_reader_eof_total 632
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 5655
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11429
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 624
telemt_me_writer_restored_same_endpoint_total 618
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 11428
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 248505576 (236.99 MB)
telemt_user_octets_to_client{user="hello"} 10189406416 (9.49 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 28
```