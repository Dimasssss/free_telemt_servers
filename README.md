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

# Server Metrics 2026-03-15 14:17:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 57787.6 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259948
telemt_connections_bad_total 2397
telemt_handshake_timeouts_total 6123
telemt_upstream_connect_attempt_total 14663
telemt_upstream_connect_success_total 14587
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15054
telemt_me_reconnect_success_total 11675
telemt_me_reader_eof_total 12450
telemt_me_idle_close_by_peer_total 12450
telemt_me_route_drop_no_conn_total 438095
telemt_me_route_drop_channel_closed_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302391
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1699
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 1026
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 733
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11899
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11644
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 241496
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 5319124804 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 210122921436 (195.69 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 57793.8 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95725
telemt_connections_bad_total 2775
telemt_handshake_timeouts_total 9315
telemt_upstream_connect_attempt_total 15938
telemt_upstream_connect_success_total 15938
telemt_upstream_connect_attempts_per_request{bucket="1"} 15938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15345
telemt_me_reconnect_success_total 12995
telemt_me_reader_eof_total 13911
telemt_me_idle_close_by_peer_total 13911
telemt_me_route_drop_no_conn_total 40836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80720
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13221
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12979
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 80711
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 1605157800 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 38595941492 (35.95 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 57786.2 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104322
telemt_connections_bad_total 1642
telemt_handshake_timeouts_total 2770
telemt_upstream_connect_attempt_total 17216
telemt_upstream_connect_success_total 17208
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 19643
telemt_me_reconnect_success_total 14256
telemt_me_reader_eof_total 15274
telemt_me_idle_close_by_peer_total 15274
telemt_me_route_drop_no_conn_total 38942
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89809
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14556
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 14248
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 89714
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 10118933740 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 53045980404 (49.40 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 57785.9 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137417
telemt_connections_bad_total 777
telemt_handshake_timeouts_total 910
telemt_upstream_connect_attempt_total 13742
telemt_upstream_connect_success_total 13739
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10891
telemt_me_reconnect_success_total 10827
telemt_me_reader_eof_total 11528
telemt_me_idle_close_by_peer_total 11528
telemt_me_route_drop_no_conn_total 53400
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125382
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 424
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10951
telemt_me_writer_restored_same_endpoint_total 10816
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 125298
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 2348393704 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 62645657716 (58.34 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 32857.5 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79174
telemt_connections_bad_total 21179
telemt_handshake_timeouts_total 1416
telemt_upstream_connect_attempt_total 10437
telemt_upstream_connect_success_total 10371
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102962
telemt_me_reconnect_success_total 8536
telemt_me_reader_eof_total 8920
telemt_me_idle_close_by_peer_total 8920
telemt_me_route_drop_no_conn_total 26708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54797
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 8549
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8432
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 54934
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 836634281 (797.88 MB)
telemt_user_octets_to_client{user="hello"} 22655793411 (21.10 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 57785.8 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346309
telemt_connections_bad_total 48391
telemt_handshake_timeouts_total 2864
telemt_upstream_connect_attempt_total 12426
telemt_upstream_connect_success_total 12351
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10194
telemt_me_reconnect_success_total 9421
telemt_me_reader_eof_total 10020
telemt_me_idle_close_by_peer_total 10020
telemt_me_route_drop_no_conn_total 159901
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284867
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 296
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9532
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9394
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 282723
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 6916926604 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 139050811844 (129.50 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 66
```