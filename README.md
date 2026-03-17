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

# Server Metrics 2026-03-17 07:56:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 47447.5 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321671
telemt_connections_bad_total 3551
telemt_handshake_timeouts_total 9830
telemt_upstream_connect_attempt_total 9754
telemt_upstream_connect_success_total 9701
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 9754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7377
telemt_me_reconnect_success_total 7348
telemt_me_reader_eof_total 7816
telemt_me_idle_close_by_peer_total 7816
telemt_me_route_drop_no_conn_total 98753
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290071
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2255
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1608
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 1108
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7425
telemt_me_writer_restored_same_endpoint_total 7327
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 289823
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 3952712808 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 123932124816 (115.42 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 47699.0 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180831
telemt_connections_bad_total 2350
telemt_handshake_timeouts_total 11923
telemt_upstream_connect_attempt_total 13017
telemt_upstream_connect_success_total 12849
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 13017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 12776
telemt_me_reconnect_success_total 10503
telemt_me_reader_eof_total 11112
telemt_me_idle_close_by_peer_total 11112
telemt_me_route_drop_no_conn_total 65110
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157243
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10673
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10487
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 157271
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 1897831340 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 62871777336 (58.55 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 47475.2 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110581
telemt_connections_bad_total 5672
telemt_handshake_timeouts_total 5165
telemt_upstream_connect_attempt_total 12384
telemt_upstream_connect_success_total 12320
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10002
telemt_me_reconnect_success_total 9942
telemt_me_reader_eof_total 10648
telemt_me_idle_close_by_peer_total 10648
telemt_me_route_drop_no_conn_total 34512
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91000
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10067
telemt_me_writer_restored_same_endpoint_total 9931
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 90956
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 6501016320 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 28232969532 (26.29 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 47534.1 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213903
telemt_connections_bad_total 6059
telemt_handshake_timeouts_total 10122
telemt_upstream_connect_attempt_total 10923
telemt_upstream_connect_success_total 10830
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 10923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9475
telemt_me_reconnect_success_total 8411
telemt_me_reader_eof_total 8945
telemt_me_idle_close_by_peer_total 8945
telemt_me_route_drop_no_conn_total 63882
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181068
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 371
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8565
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8403
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 181075
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 1896353514 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 81496316093 (75.90 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 47506.1 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137539
telemt_connections_bad_total 38878
telemt_handshake_timeouts_total 2471
telemt_upstream_connect_attempt_total 14570
telemt_upstream_connect_success_total 14381
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 14570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 15170
telemt_me_reconnect_success_total 11907
telemt_me_reader_eof_total 12553
telemt_me_idle_close_by_peer_total 12553
telemt_me_route_drop_no_conn_total 36050
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92119
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12156
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11899
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 92158
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 959955515 (915.48 MB)
telemt_user_octets_to_client{user="hello"} 43526156474 (40.54 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 47667.1 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326585
telemt_connections_bad_total 42173
telemt_handshake_timeouts_total 2972
telemt_upstream_connect_attempt_total 9863
telemt_upstream_connect_success_total 9812
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 10049
telemt_me_reconnect_success_total 7454
telemt_me_reader_eof_total 8022
telemt_me_idle_close_by_peer_total 8022
telemt_me_route_drop_no_conn_total 243297
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346730
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 363
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 202
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7643
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 7440
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 268656
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 3764294276 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 166483788304 (155.05 GB)
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 35673.5 (9h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1800
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17708
telemt_upstream_connect_success_total 17707
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15947
telemt_me_reconnect_success_total 15856
telemt_me_reader_eof_total 17349
telemt_me_idle_close_by_peer_total 17349
telemt_me_route_drop_no_conn_total 268
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1588
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15995
telemt_me_writer_restored_same_endpoint_total 15856
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1588
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 226016880 (215.55 MB)
telemt_user_octets_to_client{user="hello"} 16860522712 (15.70 GB)
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```