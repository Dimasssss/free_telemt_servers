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

# Server Metrics 2026-03-16 03:49:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 106478.4 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455560
telemt_connections_bad_total 5375
telemt_handshake_timeouts_total 15544
telemt_upstream_connect_attempt_total 25474
telemt_upstream_connect_success_total 25356
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 25474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 23491
telemt_me_reconnect_success_total 20068
telemt_me_reader_eof_total 21464
telemt_me_idle_close_by_peer_total 21464
telemt_me_route_drop_no_conn_total 501645
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477734
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2321
telemt_desync_full_logged_total 934
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 909
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 102
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20391
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 20034
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 416591
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 8524970040 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 294730234328 (274.49 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 106484.7 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184612
telemt_connections_bad_total 2971
telemt_handshake_timeouts_total 14661
telemt_upstream_connect_attempt_total 29029
telemt_upstream_connect_success_total 28954
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 29029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 30160
telemt_me_reconnect_success_total 23252
telemt_me_reader_eof_total 24915
telemt_me_idle_close_by_peer_total 24914
telemt_me_route_drop_no_conn_total 93527
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160286
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 23793
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 23236
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 159832
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 3480776825 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 83150194528 (77.44 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 106477.7 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204329
telemt_connections_bad_total 3083
telemt_handshake_timeouts_total 4008
telemt_upstream_connect_attempt_total 30092
telemt_upstream_connect_success_total 30084
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 30092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 32123
telemt_me_reconnect_success_total 24733
telemt_me_reader_eof_total 26643
telemt_me_idle_close_by_peer_total 26642
telemt_me_route_drop_no_conn_total 72804
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162967
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
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 25208
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 24725
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 162700
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 16435503585 (15.31 GB)
telemt_user_octets_to_client{user="hello"} 101779045092 (94.79 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 106477.1 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269417
telemt_connections_bad_total 1227
telemt_handshake_timeouts_total 1703
telemt_upstream_connect_attempt_total 24977
telemt_upstream_connect_success_total 24956
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 24977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 19781
telemt_me_reconnect_success_total 19664
telemt_me_reader_eof_total 20996
telemt_me_idle_close_by_peer_total 20995
telemt_me_route_drop_no_conn_total 99296
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249131
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 884
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 19904
telemt_me_writer_restored_same_endpoint_total 19653
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 249013
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 4269483148 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 112576209016 (104.84 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 81548.6 (22h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178737
telemt_connections_bad_total 31522
telemt_handshake_timeouts_total 3142
telemt_upstream_connect_attempt_total 23242
telemt_upstream_connect_success_total 23113
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 23242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 113369
telemt_me_reconnect_success_total 18897
telemt_me_reader_eof_total 20071
telemt_me_idle_close_by_peer_total 20071
telemt_me_route_drop_no_conn_total 56661
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139713
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
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 19047
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 18793
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 139349
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1951704433 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 60692576431 (56.52 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 106476.2 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682670
telemt_connections_bad_total 58744
telemt_handshake_timeouts_total 5081
telemt_upstream_connect_attempt_total 22669
telemt_upstream_connect_success_total 22549
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 22669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 18564
telemt_me_reconnect_success_total 17231
telemt_me_reader_eof_total 18393
telemt_me_idle_close_by_peer_total 18393
telemt_me_route_drop_no_conn_total 597358
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706489
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
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 17471
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 17204
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 565174
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 13047979604 (12.15 GB)
telemt_user_octets_to_client{user="hello"} 349397327064 (325.40 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 40
```