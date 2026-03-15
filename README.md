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

# Server Metrics 2026-03-15 21:26:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 83510.3 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385694
telemt_connections_bad_total 5124
telemt_handshake_timeouts_total 13815
telemt_upstream_connect_attempt_total 19923
telemt_upstream_connect_success_total 19824
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 19923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 19082
telemt_me_reconnect_success_total 15677
telemt_me_reader_eof_total 16712
telemt_me_idle_close_by_peer_total 16712
telemt_me_route_drop_no_conn_total 482805
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413259
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2030
telemt_desync_full_logged_total 797
telemt_desync_suppressed_total 1233
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 790
telemt_desync_frames_bucket_total{bucket="gt_10"} 854
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15954
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 15643
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 352321
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 7854649948 (7.32 GB)
telemt_user_octets_to_client{user="hello"} 266157827744 (247.88 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 83516.9 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160489
telemt_connections_bad_total 2870
telemt_handshake_timeouts_total 13977
telemt_upstream_connect_attempt_total 22821
telemt_upstream_connect_success_total 22746
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 22821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 607
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 25072
telemt_me_reconnect_success_total 18186
telemt_me_reader_eof_total 19444
telemt_me_idle_close_by_peer_total 19443
telemt_me_route_drop_no_conn_total 66067
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136995
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
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 18678
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 18170
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 137265
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 2621266237 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 72434595496 (67.46 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 83509.6 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159594
telemt_connections_bad_total 1741
telemt_handshake_timeouts_total 3414
telemt_upstream_connect_attempt_total 23900
telemt_upstream_connect_success_total 23892
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 23900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 27056
telemt_me_reconnect_success_total 19689
telemt_me_reader_eof_total 21153
telemt_me_idle_close_by_peer_total 21152
telemt_me_route_drop_no_conn_total 63411
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141987
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
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 20110
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 19681
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 141869
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 10989428220 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 85951624520 (80.05 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 83509.4 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231490
telemt_connections_bad_total 1189
telemt_handshake_timeouts_total 1593
telemt_upstream_connect_attempt_total 19483
telemt_upstream_connect_success_total 19465
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 19483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 15414
telemt_me_reconnect_success_total 15320
telemt_me_reader_eof_total 16322
telemt_me_idle_close_by_peer_total 16322
telemt_me_route_drop_no_conn_total 84692
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213242
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15503
telemt_me_writer_restored_same_endpoint_total 15309
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 213157
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 3997417968 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 98891645184 (92.10 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 58580.9 (16h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142385
telemt_connections_bad_total 27196
telemt_handshake_timeouts_total 2566
telemt_upstream_connect_attempt_total 16984
telemt_upstream_connect_success_total 16880
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 16984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 108226
telemt_me_reconnect_success_total 13770
telemt_me_reader_eof_total 14504
telemt_me_idle_close_by_peer_total 14504
telemt_me_route_drop_no_conn_total 46925
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108576
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 13864
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 13666
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 108704
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 1677705833 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 41267495359 (38.43 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 83508.6 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561761
telemt_connections_bad_total 58535
telemt_handshake_timeouts_total 4371
telemt_upstream_connect_attempt_total 17667
telemt_upstream_connect_success_total 17565
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 17667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14701
telemt_me_reconnect_success_total 13388
telemt_me_reader_eof_total 14239
telemt_me_idle_close_by_peer_total 14239
telemt_me_route_drop_no_conn_total 425236
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564349
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13576
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 13361
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 477874
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 11888291444 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 282647763576 (263.24 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 46
```