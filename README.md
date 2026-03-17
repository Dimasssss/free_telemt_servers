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

# Server Metrics 2026-03-17 06:44:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 43173.3 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263296
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 8368
telemt_upstream_connect_attempt_total 8958
telemt_upstream_connect_success_total 8911
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6807
telemt_me_reconnect_success_total 6782
telemt_me_reader_eof_total 7219
telemt_me_idle_close_by_peer_total 7219
telemt_me_route_drop_no_conn_total 80353
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235672
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1722
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 1189
telemt_desync_frames_bucket_total{bucket="1_2"} 395
telemt_desync_frames_bucket_total{bucket="3_10"} 866
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6853
telemt_me_writer_restored_same_endpoint_total 6761
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 235459
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 3109147084 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 103650824940 (96.53 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 43424.6 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147471
telemt_connections_bad_total 2209
telemt_handshake_timeouts_total 11214
telemt_upstream_connect_attempt_total 11943
telemt_upstream_connect_success_total 11793
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 11943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 10804
telemt_me_reconnect_success_total 9625
telemt_me_reader_eof_total 10171
telemt_me_idle_close_by_peer_total 10171
telemt_me_route_drop_no_conn_total 54503
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128317
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9749
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9609
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 128326
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 1583258376 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 54781826236 (51.02 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 43200.7 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88193
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 2792
telemt_upstream_connect_attempt_total 11517
telemt_upstream_connect_success_total 11457
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9356
telemt_me_reconnect_success_total 9304
telemt_me_reader_eof_total 9957
telemt_me_idle_close_by_peer_total 9957
telemt_me_route_drop_no_conn_total 29772
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76035
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9415
telemt_me_writer_restored_same_endpoint_total 9293
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 76017
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 6163651808 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 24340911932 (22.67 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 43259.8 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159864
telemt_connections_bad_total 5548
telemt_handshake_timeouts_total 7651
telemt_upstream_connect_attempt_total 9773
telemt_upstream_connect_success_total 9690
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 9773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_reconnect_attempts_total 7548
telemt_me_reconnect_success_total 7489
telemt_me_reader_eof_total 7962
telemt_me_idle_close_by_peer_total 7962
telemt_me_route_drop_no_conn_total 52149
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141693
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 261
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7597
telemt_me_writer_restored_same_endpoint_total 7482
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 141704
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 1548446594 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 68134941309 (63.46 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 43231.7 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119106
telemt_connections_bad_total 35315
telemt_handshake_timeouts_total 2374
telemt_upstream_connect_attempt_total 13153
telemt_upstream_connect_success_total 12982
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 13153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_reconnect_attempts_total 13988
telemt_me_reconnect_success_total 10729
telemt_me_reader_eof_total 11326
telemt_me_idle_close_by_peer_total 11326
telemt_me_route_drop_no_conn_total 30244
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78158
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 53
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10971
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 10721
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 78254
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 806719567 (769.35 MB)
telemt_user_octets_to_client{user="hello"} 35944412438 (33.48 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 43392.8 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284026
telemt_connections_bad_total 40502
telemt_handshake_timeouts_total 2262
telemt_upstream_connect_attempt_total 8822
telemt_upstream_connect_success_total 8776
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6633
telemt_me_reconnect_success_total 6603
telemt_me_reader_eof_total 7082
telemt_me_idle_close_by_peer_total 7082
telemt_me_route_drop_no_conn_total 225621
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308309
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 275
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 6702
telemt_me_writer_restored_same_endpoint_total 6593
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 230245
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 3376345876 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 156152438512 (145.43 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 31399.2 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1236
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 15588
telemt_upstream_connect_success_total 15588
telemt_upstream_connect_attempts_per_request{bucket="1"} 15588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 14045
telemt_me_reconnect_success_total 13969
telemt_me_reader_eof_total 15300
telemt_me_idle_close_by_peer_total 15300
telemt_me_route_drop_no_conn_total 128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1028
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 14096
telemt_me_writer_restored_same_endpoint_total 13969
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 1028
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 203548208 (194.12 MB)
telemt_user_octets_to_client{user="hello"} 12936887332 (12.05 GB)
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```