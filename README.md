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

# Server Metrics 2026-03-15 10:53:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 45536.6 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190986
telemt_connections_bad_total 1347
telemt_handshake_timeouts_total 4319
telemt_upstream_connect_attempt_total 11411
telemt_upstream_connect_success_total 11351
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 11448
telemt_me_reconnect_success_total 9074
telemt_me_reader_eof_total 9706
telemt_me_idle_close_by_peer_total 9706
telemt_me_route_drop_no_conn_total 414603
telemt_me_route_drop_channel_closed_total 63
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239058
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1438
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 633
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9233
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 9043
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 178310
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 3100609412 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 182694004532 (170.15 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 45543.3 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62071
telemt_connections_bad_total 2327
telemt_handshake_timeouts_total 3059
telemt_upstream_connect_attempt_total 12261
telemt_upstream_connect_success_total 12261
telemt_upstream_connect_attempts_per_request{bucket="1"} 12261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12288
telemt_me_reconnect_success_total 9964
telemt_me_reader_eof_total 10703
telemt_me_idle_close_by_peer_total 10703
telemt_me_route_drop_no_conn_total 29101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54682
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10146
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9948
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 54682
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 1035725456 (987.74 MB)
telemt_user_octets_to_client{user="hello"} 23242354492 (21.65 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 45535.9 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70351
telemt_connections_bad_total 999
telemt_handshake_timeouts_total 2456
telemt_upstream_connect_attempt_total 12702
telemt_upstream_connect_success_total 12701
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 11607
telemt_me_reconnect_success_total 10407
telemt_me_reader_eof_total 11197
telemt_me_idle_close_by_peer_total 11197
telemt_me_route_drop_no_conn_total 26511
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63853
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10537
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10403
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 63771
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 9363259124 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 39402783452 (36.70 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 45535.4 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91211
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 602
telemt_upstream_connect_attempt_total 10810
telemt_upstream_connect_success_total 10809
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8577
telemt_me_reconnect_success_total 8535
telemt_me_reader_eof_total 9114
telemt_me_idle_close_by_peer_total 9114
telemt_me_route_drop_no_conn_total 37564
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83275
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8625
telemt_me_writer_restored_same_endpoint_total 8524
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 83205
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 1618595620 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 50641225752 (47.16 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 20607.0 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35486
telemt_connections_bad_total 3847
telemt_handshake_timeouts_total 505
telemt_upstream_connect_attempt_total 6832
telemt_upstream_connect_success_total 6779
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 6832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 99989
telemt_me_reconnect_success_total 5579
telemt_me_reader_eof_total 5789
telemt_me_idle_close_by_peer_total 5789
telemt_me_route_drop_no_conn_total 12703
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30256
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5553
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5475
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 30396
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 459697009 (438.40 MB)
telemt_user_octets_to_client{user="hello"} 13069039519 (12.17 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 45534.9 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247452
telemt_connections_bad_total 44484
telemt_handshake_timeouts_total 1734
telemt_upstream_connect_attempt_total 9711
telemt_upstream_connect_success_total 9652
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 9711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 7410
telemt_me_reconnect_success_total 7367
telemt_me_reader_eof_total 7845
telemt_me_idle_close_by_peer_total 7845
telemt_me_route_drop_no_conn_total 109035
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194191
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 84
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7422
telemt_me_writer_restored_same_endpoint_total 7340
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 192560
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 4535269404 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 96539374936 (89.91 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 78
```