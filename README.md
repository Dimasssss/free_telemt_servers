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

# Server Metrics 2026-03-16 01:31:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 98206.9 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425117
telemt_connections_bad_total 5358
telemt_handshake_timeouts_total 14473
telemt_upstream_connect_attempt_total 23484
telemt_upstream_connect_success_total 23373
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 23484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 21899
telemt_me_reconnect_success_total 18485
telemt_me_reader_eof_total 19752
telemt_me_idle_close_by_peer_total 19752
telemt_me_route_drop_no_conn_total 494079
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450343
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2221
telemt_desync_full_logged_total 894
telemt_desync_suppressed_total 1327
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 867
telemt_desync_frames_bucket_total{bucket="gt_10"} 921
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18794
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 18451
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 389415
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 8285503572 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 283829283868 (264.34 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 98213.1 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175794
telemt_connections_bad_total 2959
telemt_handshake_timeouts_total 14551
telemt_upstream_connect_attempt_total 26798
telemt_upstream_connect_success_total 26723
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 26798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 28316
telemt_me_reconnect_success_total 21414
telemt_me_reader_eof_total 22919
telemt_me_idle_close_by_peer_total 22918
telemt_me_route_drop_no_conn_total 71761
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151196
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 21935
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 21398
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 151457
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 3401444473 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 78315741708 (72.94 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 98205.8 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191079
telemt_connections_bad_total 2165
telemt_handshake_timeouts_total 3673
telemt_upstream_connect_attempt_total 27899
telemt_upstream_connect_success_total 27891
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 30320
telemt_me_reconnect_success_total 22938
telemt_me_reader_eof_total 24673
telemt_me_idle_close_by_peer_total 24672
telemt_me_route_drop_no_conn_total 68469
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155056
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 23390
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 22930
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 154930
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 15477837668 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 99676225360 (92.83 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 98205.5 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257119
telemt_connections_bad_total 1217
telemt_handshake_timeouts_total 1649
telemt_upstream_connect_attempt_total 23019
telemt_upstream_connect_success_total 22998
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 23019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 18213
telemt_me_reconnect_success_total 18104
telemt_me_reader_eof_total 19304
telemt_me_idle_close_by_peer_total 19304
telemt_me_route_drop_no_conn_total 92773
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237568
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 879
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 18322
telemt_me_writer_restored_same_endpoint_total 18093
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 237480
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 4130886888 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 107954711548 (100.54 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 73277.0 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166254
telemt_connections_bad_total 29902
telemt_handshake_timeouts_total 2841
telemt_upstream_connect_attempt_total 21000
telemt_upstream_connect_success_total 20880
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 111523
telemt_me_reconnect_success_total 17060
telemt_me_reader_eof_total 18087
telemt_me_idle_close_by_peer_total 18087
telemt_me_route_drop_no_conn_total 52313
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128912
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 17190
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 16956
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 129032
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 1866980293 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 44704229759 (41.63 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 98204.5 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642086
telemt_connections_bad_total 58665
telemt_handshake_timeouts_total 4901
telemt_upstream_connect_attempt_total 20813
telemt_upstream_connect_success_total 20697
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 20813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 17100
telemt_me_reconnect_success_total 15779
telemt_me_reader_eof_total 16819
telemt_me_idle_close_by_peer_total 16819
telemt_me_route_drop_no_conn_total 581161
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678267
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16002
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 15752
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 536945
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 12740637956 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 331200274396 (308.45 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 28
```