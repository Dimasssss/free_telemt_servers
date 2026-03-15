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

# Server Metrics 2026-03-15 13:46:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 55949.5 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249816
telemt_connections_bad_total 2303
telemt_handshake_timeouts_total 5631
telemt_upstream_connect_attempt_total 14080
telemt_upstream_connect_success_total 14005
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 14560
telemt_me_reconnect_success_total 11182
telemt_me_reader_eof_total 11940
telemt_me_idle_close_by_peer_total 11940
telemt_me_route_drop_no_conn_total 434383
telemt_me_route_drop_channel_closed_total 66
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293503
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1675
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1013
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11402
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11151
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 232607
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 5166171848 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 205255765212 (191.16 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 55955.9 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91684
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 8644
telemt_upstream_connect_attempt_total 15392
telemt_upstream_connect_success_total 15392
telemt_upstream_connect_attempts_per_request{bucket="1"} 15392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 14887
telemt_me_reconnect_success_total 12542
telemt_me_reader_eof_total 13422
telemt_me_idle_close_by_peer_total 13422
telemt_me_route_drop_no_conn_total 39004
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77500
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12755
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12526
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 77493
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 1527503608 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 37326288572 (34.76 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 55948.5 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93974
telemt_connections_bad_total 1611
telemt_handshake_timeouts_total 2737
telemt_upstream_connect_attempt_total 16564
telemt_upstream_connect_success_total 16556
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 16564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 15854
telemt_me_reconnect_success_total 13701
telemt_me_reader_eof_total 14618
telemt_me_idle_close_by_peer_total 14618
telemt_me_route_drop_no_conn_total 36655
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85636
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_me_writer_removed_unexpected_total 13900
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 13693
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 85542
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 10030262320 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 51738829240 (48.19 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 55948.0 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130070
telemt_connections_bad_total 552
telemt_handshake_timeouts_total 851
telemt_upstream_connect_attempt_total 13229
telemt_upstream_connect_success_total 13226
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10465
telemt_me_reconnect_success_total 10403
telemt_me_reader_eof_total 11080
telemt_me_idle_close_by_peer_total 11080
telemt_me_route_drop_no_conn_total 50516
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118539
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 414
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10521
telemt_me_writer_restored_same_endpoint_total 10392
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 118456
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 2202945388 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 60658612176 (56.49 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 31019.4 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75007
telemt_connections_bad_total 20848
telemt_handshake_timeouts_total 1397
telemt_upstream_connect_attempt_total 9928
telemt_upstream_connect_success_total 9863
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102543
telemt_me_reconnect_success_total 8118
telemt_me_reader_eof_total 8470
telemt_me_idle_close_by_peer_total 8470
telemt_me_route_drop_no_conn_total 25195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51098
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 8124
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8014
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 51234
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 780210209 (744.07 MB)
telemt_user_octets_to_client{user="hello"} 20452504907 (19.05 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 55947.4 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331115
telemt_connections_bad_total 47912
telemt_handshake_timeouts_total 2616
telemt_upstream_connect_attempt_total 11917
telemt_upstream_connect_success_total 11846
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 9076
telemt_me_reconnect_success_total 9013
telemt_me_reader_eof_total 9586
telemt_me_idle_close_by_peer_total 9586
telemt_me_route_drop_no_conn_total 151609
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271212
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 278
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9098
telemt_me_writer_restored_same_endpoint_total 8986
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 269076
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 6438017896 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 131947247204 (122.89 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 61
```