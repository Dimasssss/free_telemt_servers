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

# Server Metrics 2026-03-17 08:57:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 51115.1 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384505
telemt_connections_bad_total 3615
telemt_handshake_timeouts_total 11637
telemt_upstream_connect_attempt_total 13170
telemt_upstream_connect_success_total 12741
telemt_upstream_connect_fail_total 429
telemt_upstream_connect_attempts_per_request{bucket="1"} 13170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 429
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 9437
telemt_me_reconnect_success_total 7921
telemt_me_reader_eof_total 8422
telemt_me_idle_close_by_peer_total 8421
telemt_me_route_drop_no_conn_total 120447
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345839
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2679
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1933
telemt_desync_frames_bucket_total{bucket="1_2"} 626
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8080
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 7899
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 347842
telemt_user_connections_current{user="hello"} 891
telemt_user_octets_from_client{user="hello"} 4845640067 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 139239728575 (129.68 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 51366.6 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209088
telemt_connections_bad_total 2373
telemt_handshake_timeouts_total 12400
telemt_upstream_connect_attempt_total 13841
telemt_upstream_connect_success_total 13656
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 13841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_reconnect_attempts_total 14422
telemt_me_reconnect_success_total 11123
telemt_me_reader_eof_total 11787
telemt_me_idle_close_by_peer_total 11787
telemt_me_route_drop_no_conn_total 76011
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184011
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 483
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11338
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11107
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 184017
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 2220972748 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 74432450428 (69.32 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 51142.7 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128229
telemt_connections_bad_total 7567
telemt_handshake_timeouts_total 7530
telemt_upstream_connect_attempt_total 13513
telemt_upstream_connect_success_total 13443
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11844
telemt_me_reconnect_success_total 10882
telemt_me_reader_eof_total 11650
telemt_me_idle_close_by_peer_total 11650
telemt_me_route_drop_no_conn_total 39574
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104112
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 281
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11053
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 10871
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 104040
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 6649839968 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 33157176828 (30.88 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 51201.8 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278976
telemt_connections_bad_total 6178
telemt_handshake_timeouts_total 10616
telemt_upstream_connect_attempt_total 11709
telemt_upstream_connect_success_total 11603
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 11709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10077
telemt_me_reconnect_success_total 9003
telemt_me_reader_eof_total 9576
telemt_me_idle_close_by_peer_total 9576
telemt_me_route_drop_no_conn_total 76310
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220207
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9175
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8995
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 220168
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 2320887978 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 92778036661 (86.41 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 51173.8 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158059
telemt_connections_bad_total 42667
telemt_handshake_timeouts_total 2716
telemt_upstream_connect_attempt_total 15599
telemt_upstream_connect_success_total 15392
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 15599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 19845
telemt_me_reconnect_success_total 12737
telemt_me_reader_eof_total 13520
telemt_me_idle_close_by_peer_total 13520
telemt_me_route_drop_no_conn_total 41424
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107774
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 315
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 13116
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12729
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 107803
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1716764799 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 49334221086 (45.95 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 51335.4 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378608
telemt_connections_bad_total 46454
telemt_handshake_timeouts_total 3815
telemt_upstream_connect_attempt_total 10535
telemt_upstream_connect_success_total 10477
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11811
telemt_me_reconnect_success_total 7933
telemt_me_reader_eof_total 8568
telemt_me_idle_close_by_peer_total 8568
telemt_me_route_drop_no_conn_total 260347
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384829
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 480
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 8172
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7919
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 306728
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 4242923384 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 176427757780 (164.31 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 39341.2 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3983
telemt_connections_bad_total 209
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 19218
telemt_upstream_connect_success_total 19205
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 19218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 17280
telemt_me_reconnect_success_total 17153
telemt_me_reader_eof_total 18721
telemt_me_idle_close_by_peer_total 18721
telemt_me_route_drop_no_conn_total 836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3710
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 17310
telemt_me_writer_restored_same_endpoint_total 17153
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 3710
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 730057524 (696.24 MB)
telemt_user_octets_to_client{user="hello"} 22194691036 (20.67 GB)
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 8
```