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

# Server Metrics 2026-03-17 08:06:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 48058.5 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331407
telemt_connections_bad_total 3563
telemt_handshake_timeouts_total 9904
telemt_upstream_connect_attempt_total 9927
telemt_upstream_connect_success_total 9873
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 9927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7503
telemt_me_reconnect_success_total 7473
telemt_me_reader_eof_total 7943
telemt_me_idle_close_by_peer_total 7943
telemt_me_route_drop_no_conn_total 101706
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299386
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2353
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1688
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 1136
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7552
telemt_me_writer_restored_same_endpoint_total 7452
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 299133
telemt_user_connections_current{user="hello"} 876
telemt_user_octets_from_client{user="hello"} 4200529628 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 126965948348 (118.25 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 48309.8 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185659
telemt_connections_bad_total 2351
telemt_handshake_timeouts_total 11952
telemt_upstream_connect_attempt_total 13173
telemt_upstream_connect_success_total 13003
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 13173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 12887
telemt_me_reconnect_success_total 10614
telemt_me_reader_eof_total 11236
telemt_me_idle_close_by_peer_total 11236
telemt_me_route_drop_no_conn_total 67311
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161899
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 420
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10785
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10598
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 161918
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 1978093696 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 64371105568 (59.95 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 48086.3 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114202
telemt_connections_bad_total 6712
telemt_handshake_timeouts_total 5362
telemt_upstream_connect_attempt_total 12572
telemt_upstream_connect_success_total 12508
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10143
telemt_me_reconnect_success_total 10082
telemt_me_reader_eof_total 10788
telemt_me_idle_close_by_peer_total 10788
telemt_me_route_drop_no_conn_total 35321
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93302
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10209
telemt_me_writer_restored_same_endpoint_total 10071
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 93256
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 6517336368 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 29593704996 (27.56 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 48145.2 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229443
telemt_connections_bad_total 6066
telemt_handshake_timeouts_total 10148
telemt_upstream_connect_attempt_total 11091
telemt_upstream_connect_success_total 10996
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5724
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9598
telemt_me_reconnect_success_total 8533
telemt_me_reader_eof_total 9088
telemt_me_idle_close_by_peer_total 9088
telemt_me_route_drop_no_conn_total 65920
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188378
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8690
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 188384
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 1985687890 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 85339749521 (79.48 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 48117.3 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140640
telemt_connections_bad_total 38997
telemt_handshake_timeouts_total 2584
telemt_upstream_connect_attempt_total 14820
telemt_upstream_connect_success_total 14624
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 14820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_reconnect_attempts_total 16618
telemt_me_reconnect_success_total 12107
telemt_me_reader_eof_total 12792
telemt_me_idle_close_by_peer_total 12792
telemt_me_route_drop_no_conn_total 37038
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94623
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 201
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12395
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 12099
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 94663
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 975554063 (930.36 MB)
telemt_user_octets_to_client{user="hello"} 44400660406 (41.35 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 48278.3 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334636
telemt_connections_bad_total 42632
telemt_handshake_timeouts_total 3148
telemt_upstream_connect_attempt_total 9980
telemt_upstream_connect_success_total 9927
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 9980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11400
telemt_me_reconnect_success_total 7525
telemt_me_reader_eof_total 8133
telemt_me_idle_close_by_peer_total 8133
telemt_me_route_drop_no_conn_total 246688
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353861
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 415
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7754
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7511
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 275784
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 3933168832 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 167739666552 (156.22 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 36284.6 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2115
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17984
telemt_upstream_connect_success_total 17983
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 16179
telemt_me_reconnect_success_total 16086
telemt_me_reader_eof_total 17612
telemt_me_idle_close_by_peer_total 17612
telemt_me_route_drop_no_conn_total 380
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1900
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 16228
telemt_me_writer_restored_same_endpoint_total 16086
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1900
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 230350892 (219.68 MB)
telemt_user_octets_to_client{user="hello"} 16997000428 (15.83 GB)
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 7
```