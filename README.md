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

# Server Metrics 2026-03-14 04:45:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 162713.3 (45h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630713
telemt_connections_bad_total 32274
telemt_handshake_timeouts_total 12966
telemt_upstream_connect_attempt_total 41586
telemt_upstream_connect_success_total 41376
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 41586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5557
telemt_me_reconnect_attempts_total 37574
telemt_me_reconnect_success_total 32890
telemt_me_reader_eof_total 35155
telemt_me_idle_close_by_peer_total 35154
telemt_me_route_drop_no_conn_total 205021
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533477
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1862
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 1236
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 775
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 33395
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32870
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 505
telemt_user_connections_total{user="hello"} 533362
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 15778145754 (14.69 GB)
telemt_user_octets_to_client{user="hello"} 258518544456 (240.76 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 162606.2 (45h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318684
telemt_connections_bad_total 2271
telemt_handshake_timeouts_total 2330
telemt_upstream_connect_attempt_total 147270
telemt_upstream_connect_success_total 146076
telemt_upstream_connect_fail_total 1194
telemt_upstream_connect_attempts_per_request{bucket="1"} 147270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1194
telemt_me_keepalive_timeout_total 3872
telemt_me_reconnect_attempts_total 171476
telemt_me_reconnect_success_total 34666
telemt_me_reader_eof_total 39852
telemt_me_idle_close_by_peer_total 39852
telemt_me_route_drop_no_conn_total 101220
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198700
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 39267
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 34649
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4601
telemt_user_connections_total{user="hello"} 301809
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 3143203163 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 97537053903 (90.84 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 162569.9 (45h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370999
telemt_connections_bad_total 2940
telemt_handshake_timeouts_total 34840
telemt_upstream_connect_attempt_total 43074
telemt_upstream_connect_success_total 43065
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3396
telemt_me_reconnect_attempts_total 36205
telemt_me_reconnect_success_total 34922
telemt_me_reader_eof_total 37544
telemt_me_idle_close_by_peer_total 37544
telemt_me_route_drop_no_conn_total 133060
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320384
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 35350
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34901
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 320164
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 12708308640 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 128306321084 (119.49 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 162545.5 (45h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472531
telemt_connections_bad_total 15581
telemt_handshake_timeouts_total 4411
telemt_upstream_connect_attempt_total 72879
telemt_upstream_connect_success_total 62355
telemt_upstream_connect_fail_total 10524
telemt_upstream_connect_attempts_per_request{bucket="1"} 72879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10524
telemt_me_keepalive_timeout_total 5289
telemt_me_reconnect_attempts_total 141273
telemt_me_reconnect_success_total 35225
telemt_me_reader_eof_total 39638
telemt_me_idle_close_by_peer_total 39630
telemt_me_route_drop_no_conn_total 169486
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401153
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1208
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 38943
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35215
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3718
telemt_user_connections_total{user="hello"} 420003
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 9206872719 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 164334649956 (153.05 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 112717.0 (31h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185127
telemt_connections_bad_total 26757
telemt_handshake_timeouts_total 1642
telemt_upstream_connect_attempt_total 40551
telemt_upstream_connect_success_total 40175
telemt_upstream_connect_fail_total 376
telemt_upstream_connect_attempts_per_request{bucket="1"} 40551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 376
telemt_me_keepalive_timeout_total 2385
telemt_me_reconnect_attempts_total 43079
telemt_me_reconnect_success_total 29657
telemt_me_reader_eof_total 31741
telemt_me_idle_close_by_peer_total 31741
telemt_me_route_drop_no_conn_total 54887
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146750
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 30342
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29639
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 151503
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 2256493241 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 68956819247 (64.22 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 162501.5 (45h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 923033
telemt_connections_bad_total 28249
telemt_handshake_timeouts_total 25629
telemt_upstream_connect_attempt_total 33786
telemt_upstream_connect_success_total 33604
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 33786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 4581
telemt_me_reconnect_attempts_total 30235
telemt_me_reconnect_success_total 25564
telemt_me_reader_eof_total 27439
telemt_me_idle_close_by_peer_total 27436
telemt_me_route_drop_no_conn_total 438901
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 861816
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 26035
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25557
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 834480
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 14531618824 (13.53 GB)
telemt_user_octets_to_client{user="hello"} 423139909032 (394.08 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 43
```