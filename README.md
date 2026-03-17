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

# Server Metrics 2026-03-17 08:26:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 49280.4 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350610
telemt_connections_bad_total 3580
telemt_handshake_timeouts_total 10381
telemt_upstream_connect_attempt_total 10158
telemt_upstream_connect_success_total 10103
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 8840
telemt_me_reconnect_success_total 7657
telemt_me_reader_eof_total 8164
telemt_me_idle_close_by_peer_total 8164
telemt_me_route_drop_no_conn_total 107841
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317295
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2469
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1772
telemt_desync_frames_bucket_total{bucket="1_2"} 570
telemt_desync_frames_bucket_total{bucket="3_10"} 1180
telemt_desync_frames_bucket_total{bucket="gt_10"} 719
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7774
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7636
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 317028
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 4506270484 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 131628408868 (122.59 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 49531.6 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195512
telemt_connections_bad_total 2359
telemt_handshake_timeouts_total 12202
telemt_upstream_connect_attempt_total 13419
telemt_upstream_connect_success_total 13243
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 13418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_reconnect_attempts_total 13082
telemt_me_reconnect_success_total 10807
telemt_me_reader_eof_total 11435
telemt_me_idle_close_by_peer_total 11435
telemt_me_route_drop_no_conn_total 71152
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171094
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10984
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10791
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 171107
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 2079231016 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 67504154444 (62.87 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 49307.8 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120722
telemt_connections_bad_total 7515
telemt_handshake_timeouts_total 6231
telemt_upstream_connect_attempt_total 12984
telemt_upstream_connect_success_total 12917
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10509
telemt_me_reconnect_success_total 10445
telemt_me_reader_eof_total 11157
telemt_me_idle_close_by_peer_total 11157
telemt_me_route_drop_no_conn_total 37586
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98072
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10578
telemt_me_writer_restored_same_endpoint_total 10434
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 98016
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 6572010080 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 31409849176 (29.25 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 49367.0 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259988
telemt_connections_bad_total 6158
telemt_handshake_timeouts_total 10438
telemt_upstream_connect_attempt_total 11274
telemt_upstream_connect_success_total 11179
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9738
telemt_me_reconnect_success_total 8672
telemt_me_reader_eof_total 9233
telemt_me_idle_close_by_peer_total 9233
telemt_me_route_drop_no_conn_total 69724
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202022
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 429
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 275
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8831
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8664
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 202013
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 2195029842 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 88905144745 (82.80 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 49339.0 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146483
telemt_connections_bad_total 39281
telemt_handshake_timeouts_total 2638
telemt_upstream_connect_attempt_total 15174
telemt_upstream_connect_success_total 14971
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 18266
telemt_me_reconnect_success_total 12408
telemt_me_reader_eof_total 13136
telemt_me_idle_close_by_peer_total 13136
telemt_me_route_drop_no_conn_total 38771
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99905
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 259
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12740
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 12400
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 99942
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 1652468415 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 47121307174 (43.89 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 49500.5 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357468
telemt_connections_bad_total 45624
telemt_handshake_timeouts_total 3543
telemt_upstream_connect_attempt_total 10156
telemt_upstream_connect_success_total 10101
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11531
telemt_me_reconnect_success_total 7655
telemt_me_reader_eof_total 8276
telemt_me_idle_close_by_peer_total 8276
telemt_me_route_drop_no_conn_total 251817
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365798
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7887
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7641
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 287711
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 4073172252 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 171166105328 (159.41 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 37506.4 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2899
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 18376
telemt_upstream_connect_success_total 18375
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 16528
telemt_me_reconnect_success_total 16435
telemt_me_reader_eof_total 17981
telemt_me_idle_close_by_peer_total 17981
telemt_me_route_drop_no_conn_total 523
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2647
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 16580
telemt_me_writer_restored_same_endpoint_total 16435
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 2647
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 712615900 (679.60 MB)
telemt_user_octets_to_client{user="hello"} 18658182152 (17.38 GB)
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 6
```