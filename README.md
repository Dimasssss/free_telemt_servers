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

# Server Metrics 2026-03-13 15:05:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 113502.4 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470779
telemt_connections_bad_total 3229
telemt_handshake_timeouts_total 8653
telemt_upstream_connect_attempt_total 28497
telemt_upstream_connect_success_total 28360
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2449
telemt_me_reconnect_attempts_total 26193
telemt_me_reconnect_success_total 22660
telemt_me_reader_eof_total 24202
telemt_me_idle_close_by_peer_total 24201
telemt_me_route_drop_no_conn_total 153402
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412810
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1349
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 23007
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22644
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 412387
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 7424830516 (6.91 GB)
telemt_user_octets_to_client{user="hello"} 191479184468 (178.33 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 113396.2 (31h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224217
telemt_connections_bad_total 1833
telemt_handshake_timeouts_total 1581
telemt_upstream_connect_attempt_total 82063
telemt_upstream_connect_success_total 81303
telemt_upstream_connect_fail_total 760
telemt_upstream_connect_attempts_per_request{bucket="1"} 82063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 760
telemt_me_keepalive_timeout_total 1399
telemt_me_reconnect_attempts_total 110802
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29431
telemt_me_idle_close_by_peer_total 29431
telemt_me_route_drop_no_conn_total 80711
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162508
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 26
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
telemt_me_writer_removed_unexpected_total 28895
telemt_me_refill_failed_total 2645
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2873
telemt_user_connections_total{user="hello"} 211928
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 2137878239 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 67208846992 (62.59 GB)
telemt_user_msgs_from_client{user="hello"} 730408
telemt_user_msgs_to_client{user="hello"} 4815037
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 113360.0 (31h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271533
telemt_connections_bad_total 2423
telemt_handshake_timeouts_total 12121
telemt_upstream_connect_attempt_total 30464
telemt_upstream_connect_success_total 30460
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2300
telemt_me_reconnect_attempts_total 25984
telemt_me_reconnect_success_total 24765
telemt_me_reader_eof_total 26536
telemt_me_idle_close_by_peer_total 26536
telemt_me_route_drop_no_conn_total 98067
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247315
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 25037
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24745
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 247231
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 9539981228 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 105722448048 (98.46 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 113335.4 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370676
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3668
telemt_upstream_connect_attempt_total 42500
telemt_upstream_connect_success_total 32353
telemt_upstream_connect_fail_total 10147
telemt_upstream_connect_attempts_per_request{bucket="1"} 42500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10147
telemt_me_keepalive_timeout_total 4158
telemt_me_reconnect_attempts_total 99725
telemt_me_reconnect_success_total 23654
telemt_me_reader_eof_total 26738
telemt_me_idle_close_by_peer_total 26731
telemt_me_route_drop_no_conn_total 133024
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320804
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1245
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26337
telemt_me_refill_failed_total 2372
telemt_me_writer_restored_same_endpoint_total 23644
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2683
telemt_user_connections_total{user="hello"} 323714
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 6882527406 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 122226103617 (113.83 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 63507.0 (17h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98128
telemt_connections_bad_total 12741
telemt_handshake_timeouts_total 1229
telemt_upstream_connect_attempt_total 26018
telemt_upstream_connect_success_total 25795
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 26018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 1039
telemt_me_reconnect_attempts_total 27630
telemt_me_reconnect_success_total 17707
telemt_me_reader_eof_total 18966
telemt_me_idle_close_by_peer_total 18966
telemt_me_route_drop_no_conn_total 29439
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76129
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 18170
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17689
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 81028
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 941416277 (897.80 MB)
telemt_user_octets_to_client{user="hello"} 24698533219 (23.00 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 113292.3 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 675891
telemt_connections_bad_total 19755
telemt_handshake_timeouts_total 21321
telemt_upstream_connect_attempt_total 23796
telemt_upstream_connect_success_total 23677
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 23796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 2540
telemt_me_reconnect_attempts_total 22685
telemt_me_reconnect_success_total 18059
telemt_me_reader_eof_total 19384
telemt_me_idle_close_by_peer_total 19381
telemt_me_route_drop_no_conn_total 323301
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639351
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18436
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18052
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 612303
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 10494388992 (9.77 GB)
telemt_user_octets_to_client{user="hello"} 319859609612 (297.89 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 65
```