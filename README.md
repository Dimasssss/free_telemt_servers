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

# Server Metrics 2026-03-15 12:20:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 50742.4 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221109
telemt_connections_bad_total 1599
telemt_handshake_timeouts_total 4645
telemt_upstream_connect_attempt_total 12888
telemt_upstream_connect_success_total 12818
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13636
telemt_me_reconnect_success_total 10264
telemt_me_reader_eof_total 10966
telemt_me_idle_close_by_peer_total 10966
telemt_me_route_drop_no_conn_total 425019
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267467
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1530
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 923
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10471
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10233
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 206579
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 3989855480 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 192772983512 (179.53 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 50748.8 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77759
telemt_connections_bad_total 2659
telemt_handshake_timeouts_total 5563
telemt_upstream_connect_attempt_total 13826
telemt_upstream_connect_success_total 13826
telemt_upstream_connect_attempts_per_request{bucket="1"} 13826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13584
telemt_me_reconnect_success_total 11248
telemt_me_reader_eof_total 12052
telemt_me_idle_close_by_peer_total 12052
telemt_me_route_drop_no_conn_total 35073
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67042
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
telemt_me_writer_removed_unexpected_total 11441
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11232
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 67041
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1374879876 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 30281575220 (28.20 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 50741.3 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81842
telemt_connections_bad_total 1032
telemt_handshake_timeouts_total 2587
telemt_upstream_connect_attempt_total 14685
telemt_upstream_connect_success_total 14677
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 14685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14241
telemt_me_reconnect_success_total 12097
telemt_me_reader_eof_total 12937
telemt_me_idle_close_by_peer_total 12937
telemt_me_route_drop_no_conn_total 31447
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74614
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
telemt_me_writer_removed_unexpected_total 12280
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12089
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 74528
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 9549939300 (8.89 GB)
telemt_user_octets_to_client{user="hello"} 44577189852 (41.52 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 50741.2 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111293
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 713
telemt_upstream_connect_attempt_total 11933
telemt_upstream_connect_success_total 11932
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9436
telemt_me_reconnect_success_total 9384
telemt_me_reader_eof_total 10009
telemt_me_idle_close_by_peer_total 10009
telemt_me_route_drop_no_conn_total 44332
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101567
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 277
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9488
telemt_me_writer_restored_same_endpoint_total 9373
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 101487
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1782351240 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 55964320540 (52.12 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 25812.5 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59276
telemt_connections_bad_total 15324
telemt_handshake_timeouts_total 868
telemt_upstream_connect_attempt_total 8382
telemt_upstream_connect_success_total 8323
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 101269
telemt_me_reconnect_success_total 6851
telemt_me_reader_eof_total 7136
telemt_me_idle_close_by_peer_total 7136
telemt_me_route_drop_no_conn_total 20795
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41742
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 6841
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6747
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 41878
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 640446293 (610.78 MB)
telemt_user_octets_to_client{user="hello"} 16263195559 (15.15 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 50740.5 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290642
telemt_connections_bad_total 47709
telemt_handshake_timeouts_total 2130
telemt_upstream_connect_attempt_total 10765
telemt_upstream_connect_success_total 10699
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 8193
telemt_me_reconnect_success_total 8138
telemt_me_reader_eof_total 8662
telemt_me_idle_close_by_peer_total 8662
telemt_me_route_drop_no_conn_total 129290
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232325
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8208
telemt_me_writer_restored_same_endpoint_total 8111
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 230684
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 4957347136 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 112040863784 (104.35 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 73
```