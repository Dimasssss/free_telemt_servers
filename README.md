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

# Server Metrics 2026-03-16 12:04:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 136199.2 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 748010
telemt_connections_bad_total 54081
telemt_handshake_timeouts_total 23977
telemt_upstream_connect_attempt_total 31420
telemt_upstream_connect_success_total 31269
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 31420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 38723
telemt_me_reconnect_success_total 24494
telemt_me_reader_eof_total 26437
telemt_me_idle_close_by_peer_total 26437
telemt_me_route_drop_no_conn_total 606275
telemt_me_route_drop_channel_closed_total 93
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689202
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3277
telemt_desync_full_logged_total 1238
telemt_desync_suppressed_total 2039
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 1339
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 124
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25205
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24459
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 625701
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 12117076956 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 362995636736 (338.07 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 136206.4 (37h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307208
telemt_connections_bad_total 3824
telemt_handshake_timeouts_total 19443
telemt_upstream_connect_attempt_total 36511
telemt_upstream_connect_success_total 36404
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 833
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 42937
telemt_me_reconnect_success_total 28998
telemt_me_reader_eof_total 31158
telemt_me_idle_close_by_peer_total 31157
telemt_me_route_drop_no_conn_total 146294
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272460
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29846
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 28982
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 848
telemt_user_connections_total{user="hello"} 272158
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 5502834709 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 135269977252 (125.98 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 136199.0 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298800
telemt_connections_bad_total 5950
telemt_handshake_timeouts_total 8654
telemt_upstream_connect_attempt_total 37739
telemt_upstream_connect_success_total 37731
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38312
telemt_me_reconnect_success_total 30875
telemt_me_reader_eof_total 33148
telemt_me_idle_close_by_peer_total 33147
telemt_me_route_drop_no_conn_total 101738
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244381
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 31421
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30867
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 243979
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 18881591829 (17.58 GB)
telemt_user_octets_to_client{user="hello"} 129147057136 (120.28 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 136198.5 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448871
telemt_connections_bad_total 1470
telemt_handshake_timeouts_total 4117
telemt_upstream_connect_attempt_total 31574
telemt_upstream_connect_success_total 31529
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 31574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 29732
telemt_me_reconnect_success_total 24729
telemt_me_reader_eof_total 26487
telemt_me_idle_close_by_peer_total 26486
telemt_me_route_drop_no_conn_total 153121
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415255
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1509
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 25217
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24718
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 415087
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 6529885966 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 159254126564 (148.32 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 111269.9 (30h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281051
telemt_connections_bad_total 50195
telemt_handshake_timeouts_total 4506
telemt_upstream_connect_attempt_total 31716
telemt_upstream_connect_success_total 31545
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 31716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121441
telemt_me_reconnect_success_total 25834
telemt_me_reader_eof_total 27446
telemt_me_idle_close_by_peer_total 27446
telemt_me_route_drop_no_conn_total 84858
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217604
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 26094
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25730
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 217224
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2829757105 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 97841073619 (91.12 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 136197.8 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 973121
telemt_connections_bad_total 77036
telemt_handshake_timeouts_total 11922
telemt_upstream_connect_attempt_total 28803
telemt_upstream_connect_success_total 28652
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 28803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 24458
telemt_me_reconnect_success_total 21836
telemt_me_reader_eof_total 23303
telemt_me_idle_close_by_peer_total 23302
telemt_me_route_drop_no_conn_total 706114
telemt_me_route_drop_channel_closed_total 134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 950074
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 432
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22185
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21809
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 808672
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 17480498648 (16.28 GB)
telemt_user_octets_to_client{user="hello"} 461886829264 (430.17 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 99
```