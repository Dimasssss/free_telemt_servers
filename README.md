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

# Server Metrics 2026-03-12 16:33:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32402.0 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170954
telemt_connections_bad_total 2040
telemt_handshake_timeouts_total 4840
telemt_upstream_connect_attempt_total 8005
telemt_upstream_connect_success_total 7975
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 8005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 7458
telemt_me_reconnect_success_total 6324
telemt_me_reader_eof_total 6667
telemt_me_idle_close_by_peer_total 6666
telemt_me_route_drop_no_conn_total 49918
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146180
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 621
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6422
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6308
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 146138
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 2466705576 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 57455265732 (53.51 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32295.1 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71808
telemt_connections_bad_total 464
telemt_handshake_timeouts_total 621
telemt_upstream_connect_attempt_total 10335
telemt_upstream_connect_success_total 10122
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 30417
telemt_me_reconnect_success_total 8497
telemt_me_reader_eof_total 9345
telemt_me_idle_close_by_peer_total 9345
telemt_me_route_drop_no_conn_total 31522
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68165
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9243
telemt_me_refill_failed_total 684
telemt_me_writer_restored_same_endpoint_total 8482
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 746
telemt_user_connections_total{user="hello"} 68150
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 775323136 (739.41 MB)
telemt_user_octets_to_client{user="hello"} 19113164932 (17.80 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32258.5 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97200
telemt_connections_bad_total 1489
telemt_handshake_timeouts_total 2029
telemt_upstream_connect_attempt_total 8986
telemt_upstream_connect_success_total 8986
telemt_upstream_connect_attempts_per_request{bucket="1"} 8986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 170
telemt_me_reconnect_attempts_total 7370
telemt_me_reconnect_success_total 7304
telemt_me_reader_eof_total 7706
telemt_me_idle_close_by_peer_total 7706
telemt_me_route_drop_no_conn_total 35875
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89690
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7369
telemt_me_writer_restored_same_endpoint_total 7284
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 89664
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2236802660 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 44903969208 (41.82 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32234.1 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133569
telemt_connections_bad_total 13063
telemt_handshake_timeouts_total 997
telemt_upstream_connect_attempt_total 7228
telemt_upstream_connect_success_total 7009
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 7228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 313
telemt_me_reconnect_attempts_total 30709
telemt_me_reconnect_success_total 5375
telemt_me_reader_eof_total 6300
telemt_me_idle_close_by_peer_total 6300
telemt_me_route_drop_no_conn_total 47577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6228
telemt_me_refill_failed_total 790
telemt_me_writer_restored_same_endpoint_total 5367
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 853
telemt_user_connections_total{user="hello"} 112549
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 2113742408 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 48398872384 (45.07 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32203.5 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77202
telemt_connections_bad_total 7388
telemt_handshake_timeouts_total 1093
telemt_upstream_connect_attempt_total 38336
telemt_upstream_connect_success_total 37941
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 38336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 43791
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4934
telemt_me_idle_close_by_peer_total 4934
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12851
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34342
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4960
telemt_me_refill_failed_total 1256
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1276
telemt_user_connections_total{user="hello"} 66963
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 602478887 (574.57 MB)
telemt_user_octets_to_client{user="hello"} 20078602714 (18.70 GB)
telemt_user_msgs_from_client{user="hello"} 520041
telemt_user_msgs_to_client{user="hello"} 1994489
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32191.2 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202679
telemt_connections_bad_total 958
telemt_handshake_timeouts_total 1578
telemt_upstream_connect_attempt_total 6877
telemt_upstream_connect_success_total 6844
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 6278
telemt_me_reconnect_success_total 5210
telemt_me_reader_eof_total 5504
telemt_me_idle_close_by_peer_total 5503
telemt_me_route_drop_no_conn_total 79267
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194115
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5312
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5203
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 193552
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 3627117468 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 85142593752 (79.30 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 71
```