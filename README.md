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

# Server Metrics 2026-03-14 20:23:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 25610.0 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132436
telemt_connections_bad_total 16073
telemt_handshake_timeouts_total 1304
telemt_upstream_connect_attempt_total 5798
telemt_upstream_connect_success_total 5795
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 194
telemt_me_reconnect_attempts_total 4507
telemt_me_reconnect_success_total 4471
telemt_me_reader_eof_total 4741
telemt_me_idle_close_by_peer_total 4741
telemt_me_route_drop_no_conn_total 47601
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109204
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 304
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4547
telemt_me_writer_restored_same_endpoint_total 4453
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 109125
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 2353437744 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 61510043324 (57.29 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 25608.7 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53834
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 962
telemt_upstream_connect_attempt_total 6617
telemt_upstream_connect_success_total 6575
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 7827
telemt_me_reconnect_success_total 5250
telemt_me_reader_eof_total 5591
telemt_me_idle_close_by_peer_total 5591
telemt_me_route_drop_no_conn_total 28215
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50085
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5403
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5245
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 50073
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1309468708 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 21424207136 (19.95 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 25613.4 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60265
telemt_connections_bad_total 389
telemt_handshake_timeouts_total 1886
telemt_upstream_connect_attempt_total 8562
telemt_upstream_connect_success_total 8472
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 8561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 104693
telemt_me_reconnect_success_total 6829
telemt_me_reader_eof_total 7291
telemt_me_idle_close_by_peer_total 7291
telemt_me_route_drop_no_conn_total 23086
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54832
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7104
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6783
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 54897
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 3807107341 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 40351897222 (37.58 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 25618.0 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77383
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 585
telemt_upstream_connect_attempt_total 6326
telemt_upstream_connect_success_total 6288
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 4824
telemt_me_reconnect_success_total 4799
telemt_me_reader_eof_total 5046
telemt_me_idle_close_by_peer_total 5046
telemt_me_route_drop_no_conn_total 33511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73223
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 590
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4853
telemt_me_writer_restored_same_endpoint_total 4797
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 73271
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1137738204 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 23934920926 (22.29 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 25611.2 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56445
telemt_connections_bad_total 4941
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 6060
telemt_upstream_connect_success_total 5990
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 6060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 11195
telemt_me_reconnect_success_total 4661
telemt_me_reader_eof_total 5064
telemt_me_idle_close_by_peer_total 5064
telemt_me_route_drop_no_conn_total 18714
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45526
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4908
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4657
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 45513
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1365715540 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 26951192592 (25.10 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 25610.6 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195520
telemt_connections_bad_total 7290
telemt_handshake_timeouts_total 2634
telemt_upstream_connect_attempt_total 5016
telemt_upstream_connect_success_total 4924
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 5016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 8606
telemt_me_reconnect_success_total 3600
telemt_me_reader_eof_total 3910
telemt_me_idle_close_by_peer_total 3910
telemt_me_route_drop_no_conn_total 109707
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179834
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3799
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3596
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 176323
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 3850654636 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 88084453860 (82.04 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 47
```