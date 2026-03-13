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

# Server Metrics 2026-03-13 15:35:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 115335.8 (32h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478913
telemt_connections_bad_total 3367
telemt_handshake_timeouts_total 8778
telemt_upstream_connect_attempt_total 28860
telemt_upstream_connect_success_total 28723
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2477
telemt_me_reconnect_attempts_total 26470
telemt_me_reconnect_success_total 22935
telemt_me_reader_eof_total 24501
telemt_me_idle_close_by_peer_total 24500
telemt_me_route_drop_no_conn_total 156344
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420379
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 891
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 23286
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22919
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 419956
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 7511293068 (7.00 GB)
telemt_user_octets_to_client{user="hello"} 195598215988 (182.17 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 115228.3 (32h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229954
telemt_connections_bad_total 1839
telemt_handshake_timeouts_total 1586
telemt_upstream_connect_attempt_total 87162
telemt_upstream_connect_success_total 86385
telemt_upstream_connect_fail_total 777
telemt_upstream_connect_attempts_per_request{bucket="1"} 87162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 964
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 777
telemt_me_keepalive_timeout_total 1407
telemt_me_reconnect_attempts_total 113554
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29515
telemt_me_idle_close_by_peer_total 29515
telemt_me_route_drop_no_conn_total 81417
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163120
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 27
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
telemt_me_writer_removed_unexpected_total 28981
telemt_me_refill_failed_total 2731
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2959
telemt_user_connections_total{user="hello"} 217531
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 2208330149 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 68714376569 (64.00 GB)
telemt_user_msgs_from_client{user="hello"} 824545
telemt_user_msgs_to_client{user="hello"} 5246528
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 115192.0 (31h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277202
telemt_connections_bad_total 2433
telemt_handshake_timeouts_total 12897
telemt_upstream_connect_attempt_total 30882
telemt_upstream_connect_success_total 30878
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2345
telemt_me_reconnect_attempts_total 26313
telemt_me_reconnect_success_total 25091
telemt_me_reader_eof_total 26890
telemt_me_idle_close_by_peer_total 26890
telemt_me_route_drop_no_conn_total 100229
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252007
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
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 25370
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25071
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 251921
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 9590923772 (8.93 GB)
telemt_user_octets_to_client{user="hello"} 107282558804 (99.91 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 115167.5 (31h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377603
telemt_connections_bad_total 15047
telemt_handshake_timeouts_total 3747
telemt_upstream_connect_attempt_total 42856
telemt_upstream_connect_success_total 32691
telemt_upstream_connect_fail_total 10165
telemt_upstream_connect_attempts_per_request{bucket="1"} 42856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10165
telemt_me_keepalive_timeout_total 4166
telemt_me_reconnect_attempts_total 102664
telemt_me_reconnect_success_total 23904
telemt_me_reader_eof_total 27071
telemt_me_idle_close_by_peer_total 27064
telemt_me_route_drop_no_conn_total 135403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327384
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1315
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 926
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26670
telemt_me_refill_failed_total 2456
telemt_me_writer_restored_same_endpoint_total 23894
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2766
telemt_user_connections_total{user="hello"} 330294
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 6914595722 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 123708004881 (115.21 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 65339.2 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101961
telemt_connections_bad_total 13070
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 26556
telemt_upstream_connect_success_total 26329
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 26556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1046
telemt_me_reconnect_attempts_total 29324
telemt_me_reconnect_success_total 18152
telemt_me_reader_eof_total 19471
telemt_me_idle_close_by_peer_total 19471
telemt_me_route_drop_no_conn_total 31127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79438
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 18655
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18134
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 84337
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 970270201 (925.32 MB)
telemt_user_octets_to_client{user="hello"} 26025002835 (24.24 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 115124.7 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693979
telemt_connections_bad_total 22390
telemt_handshake_timeouts_total 22625
telemt_upstream_connect_attempt_total 24125
telemt_upstream_connect_success_total 24003
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2553
telemt_me_reconnect_attempts_total 22925
telemt_me_reconnect_success_total 18299
telemt_me_reader_eof_total 19636
telemt_me_idle_close_by_peer_total 19633
telemt_me_route_drop_no_conn_total 329182
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653133
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18678
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18292
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 626084
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 10606781008 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 323546337644 (301.33 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 60
```