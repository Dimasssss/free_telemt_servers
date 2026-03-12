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

# Server Metrics 2026-03-12 16:59:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33938.4 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178075
telemt_connections_bad_total 2388
telemt_handshake_timeouts_total 4887
telemt_upstream_connect_attempt_total 8455
telemt_upstream_connect_success_total 8423
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 8455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 333
telemt_me_reconnect_attempts_total 7817
telemt_me_reconnect_success_total 6678
telemt_me_reader_eof_total 7044
telemt_me_idle_close_by_peer_total 7043
telemt_me_route_drop_no_conn_total 51918
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151677
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6783
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6662
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 151636
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 2566055032 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 61866695484 (57.62 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33831.1 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75096
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 629
telemt_upstream_connect_attempt_total 10688
telemt_upstream_connect_success_total 10466
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 10688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33231
telemt_me_reconnect_success_total 8751
telemt_me_reader_eof_total 9684
telemt_me_idle_close_by_peer_total 9684
telemt_me_route_drop_no_conn_total 32945
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71312
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
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
telemt_me_writer_removed_unexpected_total 9582
telemt_me_refill_failed_total 764
telemt_me_writer_restored_same_endpoint_total 8736
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 831
telemt_user_connections_total{user="hello"} 71297
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 790915212 (754.28 MB)
telemt_user_octets_to_client{user="hello"} 19803874268 (18.44 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33794.5 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101019
telemt_connections_bad_total 1493
telemt_handshake_timeouts_total 2050
telemt_upstream_connect_attempt_total 9399
telemt_upstream_connect_success_total 9399
telemt_upstream_connect_attempts_per_request{bucket="1"} 9399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 7696
telemt_me_reconnect_success_total 7626
telemt_me_reader_eof_total 8076
telemt_me_idle_close_by_peer_total 8076
telemt_me_route_drop_no_conn_total 37244
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93342
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
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7697
telemt_me_writer_restored_same_endpoint_total 7606
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 93316
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2267596796 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 48130477184 (44.82 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33770.3 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138836
telemt_connections_bad_total 13065
telemt_handshake_timeouts_total 1055
telemt_upstream_connect_attempt_total 7370
telemt_upstream_connect_success_total 7137
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 7370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 33495
telemt_me_reconnect_success_total 5409
telemt_me_reader_eof_total 6419
telemt_me_idle_close_by_peer_total 6419
telemt_me_route_drop_no_conn_total 49676
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117656
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 281
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6348
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 5401
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 939
telemt_user_connections_total{user="hello"} 117538
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2159652992 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 50392454180 (46.93 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33739.7 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82823
telemt_connections_bad_total 8944
telemt_handshake_timeouts_total 1130
telemt_upstream_connect_attempt_total 42017
telemt_upstream_connect_success_total 41600
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 42017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 46557
telemt_me_reconnect_success_total 3696
telemt_me_reader_eof_total 5030
telemt_me_idle_close_by_peer_total 5030
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13079
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34681
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_me_writer_removed_unexpected_total 5058
telemt_me_refill_failed_total 1342
telemt_me_writer_restored_same_endpoint_total 3679
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1362
telemt_user_connections_total{user="hello"} 70860
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 661651426 (631.00 MB)
telemt_user_octets_to_client{user="hello"} 21151270729 (19.70 GB)
telemt_user_msgs_from_client{user="hello"} 582456
telemt_user_msgs_to_client{user="hello"} 2152264
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33727.5 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214042
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 1726
telemt_upstream_connect_attempt_total 7258
telemt_upstream_connect_success_total 7221
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 7258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 403
telemt_me_reconnect_attempts_total 6565
telemt_me_reconnect_success_total 5495
telemt_me_reader_eof_total 5791
telemt_me_idle_close_by_peer_total 5790
telemt_me_route_drop_no_conn_total 97220
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214448
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
telemt_me_writer_removed_unexpected_total 5600
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5488
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 204384
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 3770027068 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 93972353408 (87.52 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 49
```