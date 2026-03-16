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

# Server Metrics 2026-03-16 05:15:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 111686.8 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479018
telemt_connections_bad_total 5501
telemt_handshake_timeouts_total 16812
telemt_upstream_connect_attempt_total 26582
telemt_upstream_connect_success_total 26460
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 26582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 24346
telemt_me_reconnect_success_total 20920
telemt_me_reader_eof_total 22378
telemt_me_idle_close_by_peer_total 22378
telemt_me_route_drop_no_conn_total 507513
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498322
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2447
telemt_desync_full_logged_total 972
telemt_desync_suppressed_total 1475
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 962
telemt_desync_frames_bucket_total{bucket="gt_10"} 992
telemt_pool_swap_total 107
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21253
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 20886
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 437169
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 8802631532 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 300850302456 (280.19 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 111693.3 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193137
telemt_connections_bad_total 2999
telemt_handshake_timeouts_total 14785
telemt_upstream_connect_attempt_total 30256
telemt_upstream_connect_success_total 30180
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 30255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31129
telemt_me_reconnect_success_total 24219
telemt_me_reader_eof_total 25954
telemt_me_idle_close_by_peer_total 25953
telemt_me_route_drop_no_conn_total 97672
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168307
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
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 24771
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 24203
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 167850
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 3578614309 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 87916274916 (81.88 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 111686.0 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214637
telemt_connections_bad_total 3834
telemt_handshake_timeouts_total 4165
telemt_upstream_connect_attempt_total 31390
telemt_upstream_connect_success_total 31382
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 33162
telemt_me_reconnect_success_total 25769
telemt_me_reader_eof_total 27753
telemt_me_idle_close_by_peer_total 27752
telemt_me_route_drop_no_conn_total 76115
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169545
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 26254
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 25761
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 169269
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 16533648561 (15.40 GB)
telemt_user_octets_to_client{user="hello"} 105131255660 (97.91 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 111685.4 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283074
telemt_connections_bad_total 1266
telemt_handshake_timeouts_total 2567
telemt_upstream_connect_attempt_total 26084
telemt_upstream_connect_success_total 26058
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20635
telemt_me_reconnect_success_total 20511
telemt_me_reader_eof_total 21900
telemt_me_idle_close_by_peer_total 21899
telemt_me_route_drop_no_conn_total 103563
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260549
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 888
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 20764
telemt_me_writer_restored_same_endpoint_total 20500
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 260437
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 4370907932 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 115919033440 (107.96 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 86757.0 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190451
telemt_connections_bad_total 34016
telemt_handshake_timeouts_total 3414
telemt_upstream_connect_attempt_total 24938
telemt_upstream_connect_success_total 24801
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 24937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 114794
telemt_me_reconnect_success_total 20317
telemt_me_reader_eof_total 21582
telemt_me_idle_close_by_peer_total 21582
telemt_me_route_drop_no_conn_total 60159
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148304
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 20480
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 20213
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 147938
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2032493601 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 64982279767 (60.52 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 111684.8 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714470
telemt_connections_bad_total 60841
telemt_handshake_timeouts_total 5371
telemt_upstream_connect_attempt_total 23687
telemt_upstream_connect_success_total 23561
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19320
telemt_me_reconnect_success_total 17984
telemt_me_reader_eof_total 19201
telemt_me_idle_close_by_peer_total 19201
telemt_me_route_drop_no_conn_total 608853
telemt_me_route_drop_channel_closed_total 97
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730985
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
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18235
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 17957
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 589654
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 13474931876 (12.55 GB)
telemt_user_octets_to_client{user="hello"} 364488555164 (339.46 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 59
```