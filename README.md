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

# Server Metrics 2026-03-15 22:02:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 85652.7 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391356
telemt_connections_bad_total 5175
telemt_handshake_timeouts_total 13885
telemt_upstream_connect_attempt_total 20467
telemt_upstream_connect_success_total 20366
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 20467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 19495
telemt_me_reconnect_success_total 16090
telemt_me_reader_eof_total 17163
telemt_me_idle_close_by_peer_total 17163
telemt_me_route_drop_no_conn_total 484248
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418656
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2070
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1261
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 872
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 16369
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 16056
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 357718
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 7950684464 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 270219898188 (251.66 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 85659.2 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163968
telemt_connections_bad_total 2888
telemt_handshake_timeouts_total 13985
telemt_upstream_connect_attempt_total 23364
telemt_upstream_connect_success_total 23289
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 23364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 607
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 25486
telemt_me_reconnect_success_total 18597
telemt_me_reader_eof_total 19887
telemt_me_idle_close_by_peer_total 19886
telemt_me_route_drop_no_conn_total 66847
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140335
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 19095
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 18581
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 140605
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2639492177 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 75076485188 (69.92 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 85651.9 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162473
telemt_connections_bad_total 1746
telemt_handshake_timeouts_total 3422
telemt_upstream_connect_attempt_total 24495
telemt_upstream_connect_success_total 24487
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 24495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 27522
telemt_me_reconnect_success_total 20152
telemt_me_reader_eof_total 21661
telemt_me_idle_close_by_peer_total 21660
telemt_me_route_drop_no_conn_total 64111
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144791
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
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 20578
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 20144
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 426
telemt_user_connections_total{user="hello"} 144673
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 11089799276 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 90512179680 (84.30 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 85651.6 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236350
telemt_connections_bad_total 1193
telemt_handshake_timeouts_total 1613
telemt_upstream_connect_attempt_total 19971
telemt_upstream_connect_success_total 19953
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 19971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 15772
telemt_me_reconnect_success_total 15677
telemt_me_reader_eof_total 16706
telemt_me_idle_close_by_peer_total 16706
telemt_me_route_drop_no_conn_total 86533
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217844
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 15862
telemt_me_writer_restored_same_endpoint_total 15666
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 217756
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 4038500176 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 102946389164 (95.88 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 60723.0 (16h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145820
telemt_connections_bad_total 27593
telemt_handshake_timeouts_total 2593
telemt_upstream_connect_attempt_total 17540
telemt_upstream_connect_success_total 17435
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 17540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 108684
telemt_me_reconnect_success_total 14227
telemt_me_reader_eof_total 15006
telemt_me_idle_close_by_peer_total 15006
telemt_me_route_drop_no_conn_total 47713
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111484
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
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14327
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 14123
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 111612
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 1695425493 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 42298136811 (39.39 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 85650.8 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586802
telemt_connections_bad_total 58569
telemt_handshake_timeouts_total 4409
telemt_upstream_connect_attempt_total 18138
telemt_upstream_connect_success_total 18033
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 18138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 15040
telemt_me_reconnect_success_total 13726
telemt_me_reader_eof_total 14605
telemt_me_idle_close_by_peer_total 14605
telemt_me_route_drop_no_conn_total 467828
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601803
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
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 13917
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 13699
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 489766
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 12092424064 (11.26 GB)
telemt_user_octets_to_client{user="hello"} 295393045552 (275.11 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 41
```