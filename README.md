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

# Server Metrics 2026-03-16 02:12:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 100657.2 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436503
telemt_connections_bad_total 5361
telemt_handshake_timeouts_total 14547
telemt_upstream_connect_attempt_total 24024
telemt_upstream_connect_success_total 23911
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 24024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 22351
telemt_me_reconnect_success_total 18934
telemt_me_reader_eof_total 20243
telemt_me_idle_close_by_peer_total 20243
telemt_me_route_drop_no_conn_total 496796
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461437
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2243
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 1341
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 875
telemt_desync_frames_bucket_total{bucket="gt_10"} 927
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 19251
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 18900
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 400296
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 8351364168 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 286522285160 (266.84 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 100663.7 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178154
telemt_connections_bad_total 2961
telemt_handshake_timeouts_total 14583
telemt_upstream_connect_attempt_total 27434
telemt_upstream_connect_success_total 27359
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 27434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 28866
telemt_me_reconnect_success_total 21962
telemt_me_reader_eof_total 23512
telemt_me_idle_close_by_peer_total 23511
telemt_me_route_drop_no_conn_total 89104
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154142
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
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22486
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 21946
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 153694
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3426591089 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 79391856752 (73.94 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 100656.2 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194694
telemt_connections_bad_total 2455
telemt_handshake_timeouts_total 3723
telemt_upstream_connect_attempt_total 28558
telemt_upstream_connect_success_total 28550
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 30893
telemt_me_reconnect_success_total 23509
telemt_me_reader_eof_total 25301
telemt_me_idle_close_by_peer_total 25300
telemt_me_route_drop_no_conn_total 69693
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157155
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
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 23966
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 23501
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 156985
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 16406376824 (15.28 GB)
telemt_user_octets_to_client{user="hello"} 101006476608 (94.07 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 100656.0 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260612
telemt_connections_bad_total 1218
telemt_handshake_timeouts_total 1668
telemt_upstream_connect_attempt_total 23564
telemt_upstream_connect_success_total 23543
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 23564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 18669
telemt_me_reconnect_success_total 18557
telemt_me_reader_eof_total 19795
telemt_me_idle_close_by_peer_total 19794
telemt_me_route_drop_no_conn_total 95248
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240858
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
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18782
telemt_me_writer_restored_same_endpoint_total 18546
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 240743
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 4147129120 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 108994463468 (101.51 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 75727.4 (21h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170535
telemt_connections_bad_total 30354
telemt_handshake_timeouts_total 2979
telemt_upstream_connect_attempt_total 21682
telemt_upstream_connect_success_total 21562
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 112076
telemt_me_reconnect_success_total 17610
telemt_me_reader_eof_total 18666
telemt_me_idle_close_by_peer_total 18666
telemt_me_route_drop_no_conn_total 53347
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132533
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
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 17746
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 17506
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 132651
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 1877287541 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 45040633739 (41.95 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 100655.1 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 651903
telemt_connections_bad_total 58673
telemt_handshake_timeouts_total 4930
telemt_upstream_connect_attempt_total 21326
telemt_upstream_connect_success_total 21210
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 21326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 17527
telemt_me_reconnect_success_total 16203
telemt_me_reader_eof_total 17279
telemt_me_idle_close_by_peer_total 17279
telemt_me_route_drop_no_conn_total 585615
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686177
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
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 16433
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 16176
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 544855
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 12834829328 (11.95 GB)
telemt_user_octets_to_client{user="hello"} 333714721400 (310.80 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 39
```