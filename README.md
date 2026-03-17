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

# Server Metrics 2026-03-17 07:10:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 44700.2 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283100
telemt_connections_bad_total 3389
telemt_handshake_timeouts_total 8783
telemt_upstream_connect_attempt_total 9259
telemt_upstream_connect_success_total 9209
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7016
telemt_me_reconnect_success_total 6989
telemt_me_reader_eof_total 7440
telemt_me_idle_close_by_peer_total 7440
telemt_me_route_drop_no_conn_total 86323
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254223
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1891
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 1323
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 963
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7060
telemt_me_writer_restored_same_endpoint_total 6968
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 254003
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 3312547176 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 110510614644 (102.92 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 44951.6 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159183
telemt_connections_bad_total 2236
telemt_handshake_timeouts_total 11679
telemt_upstream_connect_attempt_total 12284
telemt_upstream_connect_success_total 12129
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 12284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 11099
telemt_me_reconnect_success_total 9917
telemt_me_reader_eof_total 10485
telemt_me_idle_close_by_peer_total 10485
telemt_me_route_drop_no_conn_total 58024
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137831
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 374
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10045
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9901
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 137870
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 1696051028 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 58567719824 (54.55 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 44728.0 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94260
telemt_connections_bad_total 1132
telemt_handshake_timeouts_total 3643
telemt_upstream_connect_attempt_total 11831
telemt_upstream_connect_success_total 11769
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9582
telemt_me_reconnect_success_total 9527
telemt_me_reader_eof_total 10198
telemt_me_idle_close_by_peer_total 10198
telemt_me_route_drop_no_conn_total 31596
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81061
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9644
telemt_me_writer_restored_same_endpoint_total 9516
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 81019
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 6254184692 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 25625262576 (23.87 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 44787.0 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179383
telemt_connections_bad_total 5824
telemt_handshake_timeouts_total 9685
telemt_upstream_connect_attempt_total 10202
telemt_upstream_connect_success_total 10118
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 10202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 7899
telemt_me_reconnect_success_total 7837
telemt_me_reader_eof_total 8328
telemt_me_idle_close_by_peer_total 8328
telemt_me_route_drop_no_conn_total 56076
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154372
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7948
telemt_me_writer_restored_same_endpoint_total 7829
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 154381
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 1644026942 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 72079434301 (67.13 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 44759.0 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126777
telemt_connections_bad_total 38141
telemt_handshake_timeouts_total 2394
telemt_upstream_connect_attempt_total 13623
telemt_upstream_connect_success_total 13447
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 13623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_reconnect_attempts_total 14366
telemt_me_reconnect_success_total 11104
telemt_me_reader_eof_total 11726
telemt_me_idle_close_by_peer_total 11726
telemt_me_route_drop_no_conn_total 32806
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82833
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 69
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11348
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11096
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 82878
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 837242587 (798.46 MB)
telemt_user_octets_to_client{user="hello"} 38381817946 (35.75 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 44920.7 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299073
telemt_connections_bad_total 42156
telemt_handshake_timeouts_total 2425
telemt_upstream_connect_attempt_total 9163
telemt_upstream_connect_success_total 9115
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 6927
telemt_me_reconnect_success_total 6895
telemt_me_reader_eof_total 7377
telemt_me_idle_close_by_peer_total 7377
telemt_me_route_drop_no_conn_total 230950
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321001
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 6997
telemt_me_writer_restored_same_endpoint_total 6881
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 242939
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 3509274948 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 159312959276 (148.37 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 32926.5 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1469
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 16532
telemt_upstream_connect_success_total 16531
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14902
telemt_me_reconnect_success_total 14817
telemt_me_reader_eof_total 16210
telemt_me_idle_close_by_peer_total 16210
telemt_me_route_drop_no_conn_total 170
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1260
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 14950
telemt_me_writer_restored_same_endpoint_total 14817
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 1260
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 206969884 (197.38 MB)
telemt_user_octets_to_client{user="hello"} 13425627108 (12.50 GB)
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```