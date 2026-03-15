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

# Server Metrics 2026-03-15 12:04:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 49824.1 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216095
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 4608
telemt_upstream_connect_attempt_total 12657
telemt_upstream_connect_success_total 12588
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13454
telemt_me_reconnect_success_total 10083
telemt_me_reader_eof_total 10783
telemt_me_idle_close_by_peer_total 10783
telemt_me_route_drop_no_conn_total 423495
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262815
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1506
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 906
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 659
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10288
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10052
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 201926
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 3765835972 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 191210382844 (178.08 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 49830.8 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74736
telemt_connections_bad_total 2360
telemt_handshake_timeouts_total 4886
telemt_upstream_connect_attempt_total 13585
telemt_upstream_connect_success_total 13585
telemt_upstream_connect_attempts_per_request{bucket="1"} 13585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13387
telemt_me_reconnect_success_total 11053
telemt_me_reader_eof_total 11855
telemt_me_idle_close_by_peer_total 11855
telemt_me_route_drop_no_conn_total 34134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65031
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
telemt_me_writer_removed_unexpected_total 11244
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11037
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 65030
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1175319364 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 28116216264 (26.19 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 49823.5 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79750
telemt_connections_bad_total 1017
telemt_handshake_timeouts_total 2574
telemt_upstream_connect_attempt_total 14266
telemt_upstream_connect_success_total 14258
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 14266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13868
telemt_me_reconnect_success_total 11724
telemt_me_reader_eof_total 12562
telemt_me_idle_close_by_peer_total 12562
telemt_me_route_drop_no_conn_total 30485
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72680
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
telemt_me_writer_removed_unexpected_total 11905
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11716
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 72596
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 9535991788 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 44106935436 (41.08 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 49822.9 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108284
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 704
telemt_upstream_connect_attempt_total 11725
telemt_upstream_connect_success_total 11724
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9273
telemt_me_reconnect_success_total 9225
telemt_me_reader_eof_total 9846
telemt_me_idle_close_by_peer_total 9846
telemt_me_route_drop_no_conn_total 42953
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98761
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9325
telemt_me_writer_restored_same_endpoint_total 9214
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 98681
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1753294484 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 55101203844 (51.32 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 24894.4 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56963
telemt_connections_bad_total 15128
telemt_handshake_timeouts_total 853
telemt_upstream_connect_attempt_total 8144
telemt_upstream_connect_success_total 8085
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 101074
telemt_me_reconnect_success_total 6658
telemt_me_reader_eof_total 6927
telemt_me_idle_close_by_peer_total 6927
telemt_me_route_drop_no_conn_total 20050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39697
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6646
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6554
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 39834
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 576093105 (549.41 MB)
telemt_user_octets_to_client{user="hello"} 15484299391 (14.42 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 49822.2 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283679
telemt_connections_bad_total 47664
telemt_handshake_timeouts_total 2075
telemt_upstream_connect_attempt_total 10574
telemt_upstream_connect_success_total 10510
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 10574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 8048
telemt_me_reconnect_success_total 7997
telemt_me_reader_eof_total 8518
telemt_me_idle_close_by_peer_total 8518
telemt_me_route_drop_no_conn_total 125827
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225644
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8064
telemt_me_writer_restored_same_endpoint_total 7970
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 224005
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 4882708004 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 108673915388 (101.21 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 68
```