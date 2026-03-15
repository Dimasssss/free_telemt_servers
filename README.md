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

# Server Metrics 2026-03-15 23:33:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 91164.4 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404501
telemt_connections_bad_total 5346
telemt_handshake_timeouts_total 14068
telemt_upstream_connect_attempt_total 21810
telemt_upstream_connect_success_total 21705
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 21810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 20575
telemt_me_reconnect_success_total 17167
telemt_me_reader_eof_total 18330
telemt_me_idle_close_by_peer_total 18330
telemt_me_route_drop_no_conn_total 488717
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431047
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2118
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 1281
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 815
telemt_desync_frames_bucket_total{bucket="gt_10"} 894
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 17461
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 17133
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 370109
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 8062714832 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 277381858456 (258.33 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 91171.1 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169192
telemt_connections_bad_total 2906
telemt_handshake_timeouts_total 14190
telemt_upstream_connect_attempt_total 24846
telemt_upstream_connect_success_total 24771
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 24846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 608
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 26710
telemt_me_reconnect_success_total 19814
telemt_me_reader_eof_total 21203
telemt_me_idle_close_by_peer_total 21202
telemt_me_route_drop_no_conn_total 68802
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145202
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 20324
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 19798
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 145471
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 3370339921 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 76459953156 (71.21 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 91163.5 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167499
telemt_connections_bad_total 1769
telemt_handshake_timeouts_total 3521
telemt_upstream_connect_attempt_total 25997
telemt_upstream_connect_success_total 25989
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 25997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 28764
telemt_me_reconnect_success_total 21389
telemt_me_reader_eof_total 23002
telemt_me_idle_close_by_peer_total 23001
telemt_me_route_drop_no_conn_total 66070
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149558
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21826
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 21381
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 149440
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 13087986796 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 97405248740 (90.72 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 91163.4 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246180
telemt_connections_bad_total 1203
telemt_handshake_timeouts_total 1625
telemt_upstream_connect_attempt_total 21267
telemt_upstream_connect_success_total 21247
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 21267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 16808
telemt_me_reconnect_success_total 16708
telemt_me_reader_eof_total 17811
telemt_me_idle_close_by_peer_total 17811
telemt_me_route_drop_no_conn_total 89569
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227456
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 867
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16904
telemt_me_writer_restored_same_endpoint_total 16697
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 227368
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 4095592700 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 106516929292 (99.20 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 66234.8 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155301
telemt_connections_bad_total 28578
telemt_handshake_timeouts_total 2818
telemt_upstream_connect_attempt_total 19079
telemt_upstream_connect_success_total 18969
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 19079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 109958
telemt_me_reconnect_success_total 15499
telemt_me_reader_eof_total 16388
telemt_me_idle_close_by_peer_total 16388
telemt_me_route_drop_no_conn_total 49408
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119536
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 15613
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 15395
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 119662
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 1773799325 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42674129271 (39.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 91162.5 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613399
telemt_connections_bad_total 58578
telemt_handshake_timeouts_total 4737
telemt_upstream_connect_attempt_total 19277
telemt_upstream_connect_success_total 19169
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 15918
telemt_me_reconnect_success_total 14603
telemt_me_reader_eof_total 15553
telemt_me_idle_close_by_peer_total 15553
telemt_me_route_drop_no_conn_total 564527
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653379
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 326
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14808
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 14576
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 513848
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 12517174360 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 318408867056 (296.54 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 34
```