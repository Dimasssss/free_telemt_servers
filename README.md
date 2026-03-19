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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 06:39:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 31839.1 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513084
telemt_connections_bad_total 56291
telemt_connections_current 1298
telemt_connections_me_current 1298
telemt_handshake_timeouts_total 22473
telemt_upstream_connect_attempt_total 6169
telemt_upstream_connect_success_total 6061
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 6169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5603
telemt_me_reconnect_success_total 4459
telemt_me_reader_eof_total 4729
telemt_me_idle_close_by_peer_total 4728
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 139046
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381902
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2408
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1710
telemt_desync_frames_bucket_total{bucket="1_2"} 807
telemt_desync_frames_bucket_total{bucket="3_10"} 941
telemt_desync_frames_bucket_total{bucket="gt_10"} 660
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4541
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4442
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 379146
telemt_user_connections_current{user="hello"} 1298
telemt_user_octets_from_client{user="hello"} 5188194608 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 128796090964 (119.95 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 31843.0 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087725
telemt_connections_bad_total 61842
telemt_connections_current 3635
telemt_connections_me_current 3635
telemt_handshake_timeouts_total 29022
telemt_upstream_connect_attempt_total 5975
telemt_upstream_connect_success_total 5867
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 5975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 5398
telemt_me_reconnect_success_total 4250
telemt_me_reader_eof_total 4517
telemt_me_idle_close_by_peer_total 4517
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 354714
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901612
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3854
telemt_desync_full_logged_total 1333
telemt_desync_suppressed_total 2521
telemt_desync_frames_bucket_total{bucket="1_2"} 696
telemt_desync_frames_bucket_total{bucket="3_10"} 1454
telemt_desync_frames_bucket_total{bucket="gt_10"} 1704
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4364
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4230
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 901556
telemt_user_connections_current{user="hello"} 3635
telemt_user_octets_from_client{user="hello"} 19314216132 (17.99 GB)
telemt_user_octets_to_client{user="hello"} 398818768904 (371.43 GB)
telemt_user_unique_ips_current{user="hello"} 1257
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 31840.6 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942958
telemt_connections_bad_total 148092
telemt_connections_current 2971
telemt_connections_me_current 2971
telemt_handshake_timeouts_total 28330
telemt_upstream_connect_attempt_total 5819
telemt_upstream_connect_success_total 5819
telemt_upstream_connect_attempts_per_request{bucket="1"} 5819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4226
telemt_me_reconnect_success_total 4207
telemt_me_reader_eof_total 4457
telemt_me_idle_close_by_peer_total 4457
telemt_me_route_drop_no_conn_total 298266
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693137
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3408
telemt_desync_full_logged_total 1087
telemt_desync_suppressed_total 2321
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1226
telemt_desync_frames_bucket_total{bucket="gt_10"} 1551
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4284
telemt_me_writer_restored_same_endpoint_total 4191
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 692822
telemt_user_connections_current{user="hello"} 2971
telemt_user_octets_from_client{user="hello"} 13032047728 (12.14 GB)
telemt_user_octets_to_client{user="hello"} 390050731928 (363.26 GB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 31893.5 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1000474
telemt_connections_bad_total 88513
telemt_connections_current 2783
telemt_connections_me_current 2783
telemt_handshake_timeouts_total 24154
telemt_upstream_connect_attempt_total 5627
telemt_upstream_connect_success_total 5627
telemt_upstream_connect_attempts_per_request{bucket="1"} 5627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5060
telemt_me_reconnect_success_total 4009
telemt_me_reader_eof_total 4263
telemt_me_idle_close_by_peer_total 4262
telemt_me_route_drop_no_conn_total 327727
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682614
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2594
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 1661
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 1030
telemt_desync_frames_bucket_total{bucket="gt_10"} 1105
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4099
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 3985
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 681505
telemt_user_connections_current{user="hello"} 2783
telemt_user_octets_from_client{user="hello"} 10738272884 (10.00 GB)
telemt_user_octets_to_client{user="hello"} 257094656520 (239.44 GB)
telemt_user_unique_ips_current{user="hello"} 947
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 31836.7 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1233465
telemt_connections_bad_total 352889
telemt_connections_current 2749
telemt_connections_me_current 2749
telemt_handshake_timeouts_total 29720
telemt_upstream_connect_attempt_total 5671
telemt_upstream_connect_success_total 5636
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4054
telemt_me_reconnect_success_total 4026
telemt_me_reader_eof_total 4263
telemt_me_idle_close_by_peer_total 4263
telemt_me_route_drop_no_conn_total 300935
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728542
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3617
telemt_desync_full_logged_total 1159
telemt_desync_suppressed_total 2458
telemt_desync_frames_bucket_total{bucket="1_2"} 815
telemt_desync_frames_bucket_total{bucket="3_10"} 1602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1200
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4072
telemt_me_writer_restored_same_endpoint_total 4002
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 728351
telemt_user_connections_current{user="hello"} 2749
telemt_user_octets_from_client{user="hello"} 17385664808 (16.19 GB)
telemt_user_octets_to_client{user="hello"} 382447406204 (356.18 GB)
telemt_user_unique_ips_current{user="hello"} 1030
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 31848.6 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204233
telemt_connections_bad_total 12218
telemt_connections_current 786
telemt_connections_me_current 786
telemt_handshake_timeouts_total 1606
telemt_upstream_connect_attempt_total 8521
telemt_upstream_connect_success_total 8304
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 8521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_reconnect_attempts_total 11136
telemt_me_reconnect_success_total 6696
telemt_me_reader_eof_total 7090
telemt_me_idle_close_by_peer_total 7090
telemt_me_route_drop_no_conn_total 83249
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179285
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6865
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6666
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 179274
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 2878064992 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 95866443796 (89.28 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 31839.4 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753396
telemt_connections_bad_total 86043
telemt_connections_current 2962
telemt_connections_me_current 2962
telemt_handshake_timeouts_total 32958
telemt_upstream_connect_attempt_total 6399
telemt_upstream_connect_success_total 6399
telemt_upstream_connect_attempts_per_request{bucket="1"} 6399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4811
telemt_me_reconnect_success_total 4797
telemt_me_reader_eof_total 5067
telemt_me_idle_close_by_peer_total 5067
telemt_me_route_drop_no_conn_total 262000
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606801
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3450
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2232
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1330
telemt_desync_frames_bucket_total{bucket="gt_10"} 1454
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4850
telemt_me_writer_restored_same_endpoint_total 4782
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 606602
telemt_user_connections_current{user="hello"} 2962
telemt_user_octets_from_client{user="hello"} 8922864328 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 343589473796 (319.99 GB)
telemt_user_unique_ips_current{user="hello"} 941
telemt_user_unique_ips_recent_window{user="hello"} 372
```