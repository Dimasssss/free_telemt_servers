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

# Server Metrics 2026-03-17 04:37:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 35527.3 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188544
telemt_connections_bad_total 2534
telemt_handshake_timeouts_total 6995
telemt_upstream_connect_attempt_total 7603
telemt_upstream_connect_success_total 7561
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5803
telemt_me_reconnect_success_total 5784
telemt_me_reader_eof_total 6152
telemt_me_idle_close_by_peer_total 6152
telemt_me_route_drop_no_conn_total 59979
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170901
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1083
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 702
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5838
telemt_me_writer_restored_same_endpoint_total 5763
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 170705
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 2415812020 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 78622696740 (73.22 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 35778.5 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105024
telemt_connections_bad_total 2099
telemt_handshake_timeouts_total 3569
telemt_upstream_connect_attempt_total 10006
telemt_upstream_connect_success_total 9879
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 10006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_reconnect_attempts_total 9282
telemt_me_reconnect_success_total 8112
telemt_me_reader_eof_total 8582
telemt_me_idle_close_by_peer_total 8582
telemt_me_route_drop_no_conn_total 43015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95117
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 254
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8225
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8096
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 95119
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 1304308572 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 43534902708 (40.55 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 35554.9 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68137
telemt_connections_bad_total 969
telemt_handshake_timeouts_total 2409
telemt_upstream_connect_attempt_total 9478
telemt_upstream_connect_success_total 9427
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 7678
telemt_me_reconnect_success_total 7635
telemt_me_reader_eof_total 8185
telemt_me_idle_close_by_peer_total 8185
telemt_me_route_drop_no_conn_total 22555
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57929
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7731
telemt_me_writer_restored_same_endpoint_total 7624
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 57912
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 5876364488 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 19153737184 (17.84 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 35613.9 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109637
telemt_connections_bad_total 3627
telemt_handshake_timeouts_total 2840
telemt_upstream_connect_attempt_total 8203
telemt_upstream_connect_success_total 8133
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 8203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 6350
telemt_me_reconnect_success_total 6302
telemt_me_reader_eof_total 6710
telemt_me_idle_close_by_peer_total 6710
telemt_me_route_drop_no_conn_total 36981
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99875
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6395
telemt_me_writer_restored_same_endpoint_total 6295
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 99894
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 1088378002 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 46415666625 (43.23 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 35585.8 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78794
telemt_connections_bad_total 17225
telemt_handshake_timeouts_total 1397
telemt_upstream_connect_attempt_total 10584
telemt_upstream_connect_success_total 10452
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 10584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_reconnect_attempts_total 10921
telemt_me_reconnect_success_total 8669
telemt_me_reader_eof_total 9157
telemt_me_idle_close_by_peer_total 9157
telemt_me_route_drop_no_conn_total 22991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57957
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8857
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8661
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 57953
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 651020600 (620.86 MB)
telemt_user_octets_to_client{user="hello"} 23064368880 (21.48 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 35746.7 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211223
telemt_connections_bad_total 28878
telemt_handshake_timeouts_total 1256
telemt_upstream_connect_attempt_total 7458
telemt_upstream_connect_success_total 7418
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5668
telemt_me_reconnect_success_total 5644
telemt_me_reader_eof_total 6053
telemt_me_idle_close_by_peer_total 6053
telemt_me_route_drop_no_conn_total 191202
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252770
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5723
telemt_me_writer_restored_same_endpoint_total 5634
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 175022
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 2681863640 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 137856945256 (128.39 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 23753.3 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 11963
telemt_upstream_connect_success_total 11963
telemt_upstream_connect_attempts_per_request{bucket="1"} 11963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 10768
telemt_me_reconnect_success_total 10708
telemt_me_reader_eof_total 11774
telemt_me_idle_close_by_peer_total 11774
telemt_me_route_drop_no_conn_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 10811
telemt_me_writer_restored_same_endpoint_total 10708
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 157584760 (150.28 MB)
telemt_user_octets_to_client{user="hello"} 24357516 (23.23 MB)
```