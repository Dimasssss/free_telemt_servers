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

# Server Metrics 2026-03-12 12:33:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17979.7 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95735
telemt_connections_bad_total 538
telemt_handshake_timeouts_total 3419
telemt_upstream_connect_attempt_total 4376
telemt_upstream_connect_success_total 4356
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 3457
telemt_me_reconnect_success_total 3435
telemt_me_reader_eof_total 3586
telemt_me_idle_close_by_peer_total 3585
telemt_me_route_drop_no_conn_total 26714
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86074
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3457
telemt_me_writer_restored_same_endpoint_total 3419
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 86041
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1194590488 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 28151782564 (26.22 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17872.3 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38660
telemt_connections_bad_total 334
telemt_handshake_timeouts_total 306
telemt_upstream_connect_attempt_total 5434
telemt_upstream_connect_success_total 5303
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 5434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 18845
telemt_me_reconnect_success_total 4398
telemt_me_reader_eof_total 4892
telemt_me_idle_close_by_peer_total 4892
telemt_me_route_drop_no_conn_total 16759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36764
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4865
telemt_me_refill_failed_total 451
telemt_me_writer_restored_same_endpoint_total 4383
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 36765
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 417308288 (397.98 MB)
telemt_user_octets_to_client{user="hello"} 9576881376 (8.92 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17835.9 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52285
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 504
telemt_upstream_connect_attempt_total 4909
telemt_upstream_connect_success_total 4909
telemt_upstream_connect_attempts_per_request{bucket="1"} 4909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 4008
telemt_me_reconnect_success_total 3978
telemt_me_reader_eof_total 4186
telemt_me_idle_close_by_peer_total 4186
telemt_me_route_drop_no_conn_total 18327
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49224
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3999
telemt_me_writer_restored_same_endpoint_total 3958
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 49207
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1571875452 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 31493586348 (29.33 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17811.7 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66516
telemt_connections_bad_total 1082
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 4774
telemt_upstream_connect_success_total 4662
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 4774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 10284
telemt_me_reconnect_success_total 3741
telemt_me_reader_eof_total 4068
telemt_me_idle_close_by_peer_total 4068
telemt_me_route_drop_no_conn_total 22346
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60881
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3992
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3733
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 60879
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1074674628 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 29981800728 (27.92 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17781.1 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36780
telemt_connections_bad_total 3377
telemt_handshake_timeouts_total 639
telemt_upstream_connect_attempt_total 5982
telemt_upstream_connect_success_total 5766
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 5982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 21753
telemt_me_reconnect_success_total 3572
telemt_me_reader_eof_total 4137
telemt_me_idle_close_by_peer_total 4137
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 11113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30511
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 380
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4161
telemt_me_refill_failed_total 569
telemt_me_writer_restored_same_endpoint_total 3555
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 31786
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 225270667 (214.83 MB)
telemt_user_octets_to_client{user="hello"} 7943726115 (7.40 GB)
telemt_user_msgs_from_client{user="hello"} 16635
telemt_user_msgs_to_client{user="hello"} 72967
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17768.0 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99719
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 916
telemt_upstream_connect_attempt_total 3552
telemt_upstream_connect_success_total 3535
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 2651
telemt_me_reconnect_success_total 2629
telemt_me_reader_eof_total 2770
telemt_me_idle_close_by_peer_total 2770
telemt_me_route_drop_no_conn_total 41226
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94817
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2662
telemt_me_writer_restored_same_endpoint_total 2622
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 94784
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 2435301596 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 46219618588 (43.05 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 58
```