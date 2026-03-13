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

# Server Metrics 2026-03-13 13:07:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 106477.3 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437605
telemt_connections_bad_total 3212
telemt_handshake_timeouts_total 8433
telemt_upstream_connect_attempt_total 26997
telemt_upstream_connect_success_total 26870
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 26997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2400
telemt_me_reconnect_attempts_total 25048
telemt_me_reconnect_success_total 21522
telemt_me_reader_eof_total 22984
telemt_me_idle_close_by_peer_total 22983
telemt_me_route_drop_no_conn_total 139485
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381269
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1289
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 832
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 21855
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21506
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 380855
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 6955840300 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 165510232340 (154.14 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 106371.3 (29h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203364
telemt_connections_bad_total 1679
telemt_handshake_timeouts_total 1504
telemt_upstream_connect_attempt_total 64009
telemt_upstream_connect_success_total 63290
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 64009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 611
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 1384
telemt_me_reconnect_attempts_total 100742
telemt_me_reconnect_success_total 25980
telemt_me_reader_eof_total 29076
telemt_me_idle_close_by_peer_total 29076
telemt_me_route_drop_no_conn_total 79500
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160200
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28540
telemt_me_refill_failed_total 2332
telemt_me_writer_restored_same_endpoint_total 25963
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2560
telemt_user_connections_total{user="hello"} 191956
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1964164356 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 62830625831 (58.52 GB)
telemt_user_msgs_from_client{user="hello"} 483059
telemt_user_msgs_to_client{user="hello"} 3385121
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 106335.2 (29h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247171
telemt_connections_bad_total 2070
telemt_handshake_timeouts_total 8998
telemt_upstream_connect_attempt_total 28750
telemt_upstream_connect_success_total 28746
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2241
telemt_me_reconnect_attempts_total 24573
telemt_me_reconnect_success_total 23360
telemt_me_reader_eof_total 25025
telemt_me_idle_close_by_peer_total 25025
telemt_me_route_drop_no_conn_total 90900
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227154
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 23615
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23340
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 227069
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 9420730028 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 99035008876 (92.23 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 106310.5 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344584
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 3409
telemt_upstream_connect_attempt_total 40543
telemt_upstream_connect_success_total 30446
telemt_upstream_connect_fail_total 10096
telemt_upstream_connect_attempts_per_request{bucket="1"} 40542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10096
telemt_me_keepalive_timeout_total 4117
telemt_me_reconnect_attempts_total 93614
telemt_me_reconnect_success_total 22060
telemt_me_reader_eof_total 24966
telemt_me_idle_close_by_peer_total 24959
telemt_me_route_drop_no_conn_total 123465
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296302
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1070
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 756
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24576
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 22050
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2516
telemt_user_connections_total{user="hello"} 299213
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 6039403950 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 112641647853 (104.91 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 56481.9 (15h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83557
telemt_connections_bad_total 11171
telemt_handshake_timeouts_total 1190
telemt_upstream_connect_attempt_total 24019
telemt_upstream_connect_success_total 23827
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 24019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 986
telemt_me_reconnect_attempts_total 26008
telemt_me_reconnect_success_total 16090
telemt_me_reader_eof_total 17268
telemt_me_idle_close_by_peer_total 17268
telemt_me_route_drop_no_conn_total 24778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63621
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 16539
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16072
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 68530
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 601605969 (573.74 MB)
telemt_user_octets_to_client{user="hello"} 19201666411 (17.88 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 106267.2 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613694
telemt_connections_bad_total 17869
telemt_handshake_timeouts_total 16271
telemt_upstream_connect_attempt_total 22497
telemt_upstream_connect_success_total 22382
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2503
telemt_me_reconnect_attempts_total 21708
telemt_me_reconnect_success_total 17084
telemt_me_reader_eof_total 18340
telemt_me_idle_close_by_peer_total 18337
telemt_me_route_drop_no_conn_total 300274
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585711
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17451
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17077
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 558760
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 9838508520 (9.16 GB)
telemt_user_octets_to_client{user="hello"} 297267223008 (276.85 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 62
```