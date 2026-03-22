# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 11:11:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 50731.0 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1399075
telemt_connections_bad_total 70953
telemt_connections_current 1784
telemt_connections_me_current 1784
telemt_handshake_timeouts_total 63962
telemt_upstream_connect_attempt_total 19522
telemt_upstream_connect_success_total 19521
telemt_upstream_connect_attempts_per_request{bucket="1"} 19521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 667
telemt_me_reconnect_success_total 319
telemt_me_reader_eof_total 314
telemt_me_idle_close_by_peer_total 314
telemt_me_route_drop_no_conn_total 789242
telemt_me_route_drop_channel_closed_total 393
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1174144
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 410
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 7479
telemt_desync_full_logged_total 2226
telemt_desync_suppressed_total 5253
telemt_desync_frames_bucket_total{bucket="1_2"} 2162
telemt_desync_frames_bucket_total{bucket="3_10"} 2812
telemt_desync_frames_bucket_total{bucket="gt_10"} 2505
telemt_pool_swap_total 56
telemt_pool_force_close_total 1630
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 236
telemt_me_draining_writers_reap_progress_total 17771
telemt_me_writer_removed_unexpected_total 309
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1255
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16745
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16141
telemt_me_writer_teardown_success_total{mode="normal"} 18000
telemt_me_writer_teardown_noop_total 17773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35773
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.949183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35773
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 236
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1171976
telemt_user_connections_current{user="hello"} 1784
telemt_user_octets_from_client{user="hello"} 18968112332 (17.67 GB)
telemt_user_octets_to_client{user="hello"} 366776017412 (341.59 GB)
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 309
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 64097.2 (17h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2265917
telemt_connections_bad_total 188004
telemt_connections_current 2017
telemt_connections_me_current 2017
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 53068
telemt_upstream_connect_attempt_total 43207
telemt_upstream_connect_success_total 42702
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 43147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3321
telemt_me_reconnect_success_total 1453
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_route_drop_no_conn_total 1803785
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1779648
telemt_me_endpoint_quarantine_total 555
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 7231
telemt_desync_full_logged_total 4084
telemt_desync_suppressed_total 3147
telemt_desync_frames_bucket_total{bucket="1_2"} 1651
telemt_desync_frames_bucket_total{bucket="3_10"} 2841
telemt_desync_frames_bucket_total{bucket="gt_10"} 2739
telemt_pool_swap_total 65
telemt_pool_force_close_total 1787
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 25580
telemt_me_writer_removed_unexpected_total 1297
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2820
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24054
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23793
telemt_me_writer_teardown_success_total{mode="normal"} 26874
telemt_me_writer_teardown_noop_total 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.632569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1201
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1791581
telemt_user_connections_current{user="hello"} 2017
telemt_user_octets_from_client{user="hello"} 23439395355 (21.83 GB)
telemt_user_octets_to_client{user="hello"} 469464935018 (437.22 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1276
telemt_user_unique_ips_recent_window{user="hello"} 817
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 138957.0 (38h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11895709
telemt_connections_bad_total 1014926
telemt_connections_current 4797
telemt_connections_me_current 4797
telemt_handshake_timeouts_total 317678
telemt_upstream_connect_attempt_total 50617
telemt_upstream_connect_success_total 50537
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2170
telemt_me_reconnect_success_total 1113
telemt_me_reader_eof_total 1094
telemt_me_idle_close_by_peer_total 1093
telemt_me_route_drop_no_conn_total 9088187
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9497583
telemt_me_endpoint_quarantine_total 886
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1034
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 39148
telemt_desync_full_logged_total 12607
telemt_desync_suppressed_total 26541
telemt_desync_frames_bucket_total{bucket="1_2"} 8817
telemt_desync_frames_bucket_total{bucket="3_10"} 15278
telemt_desync_frames_bucket_total{bucket="gt_10"} 15053
telemt_pool_swap_total 150
telemt_pool_force_close_total 5043
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 785
telemt_me_draining_writers_reap_progress_total 46155
telemt_me_writer_removed_unexpected_total 1054
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41112
telemt_me_writer_teardown_success_total{mode="normal"} 46621
telemt_me_writer_teardown_noop_total 46199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92820
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.232811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92820
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 785
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 969
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9486678
telemt_user_connections_current{user="hello"} 4797
telemt_user_octets_from_client{user="hello"} 143830367344 (133.95 GB)
telemt_user_octets_to_client{user="hello"} 2749622520508 (2.50 TB)
telemt_user_unique_ips_current{user="hello"} 1695
telemt_user_unique_ips_recent_window{user="hello"} 1189
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 138958.4 (38h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9117158
telemt_connections_bad_total 814960
telemt_connections_current 3901
telemt_connections_me_current 3901
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 278739
telemt_upstream_connect_attempt_total 57241
telemt_upstream_connect_success_total 56663
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 56927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3190
telemt_me_reconnect_success_total 1298
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 3699464
telemt_me_route_drop_channel_closed_total 381
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6796983
telemt_me_endpoint_quarantine_total 881
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 1065
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 30803
telemt_desync_full_logged_total 10392
telemt_desync_suppressed_total 20411
telemt_desync_frames_bucket_total{bucket="1_2"} 7545
telemt_desync_frames_bucket_total{bucket="3_10"} 11872
telemt_desync_frames_bucket_total{bucket="gt_10"} 11386
telemt_pool_swap_total 149
telemt_pool_force_close_total 4570
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 522
telemt_me_draining_writers_reap_progress_total 44744
telemt_me_writer_removed_unexpected_total 1223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41918
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40174
telemt_me_writer_teardown_success_total{mode="normal"} 45863
telemt_me_writer_teardown_noop_total 44752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 69.527912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 522
telemt_me_refill_failed_total 103
telemt_me_writer_restored_same_endpoint_total 1114
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6718493
telemt_user_connections_current{user="hello"} 3901
telemt_user_octets_from_client{user="hello"} 175824601739 (163.75 GB)
telemt_user_octets_to_client{user="hello"} 3092199875046 (2.81 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1498
telemt_user_unique_ips_recent_window{user="hello"} 675
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 138923.4 (38h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8652648
telemt_connections_bad_total 716763
telemt_connections_current 4688
telemt_connections_me_current 4688
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 277555
telemt_upstream_connect_attempt_total 61340
telemt_upstream_connect_success_total 60630
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1385
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3720
telemt_me_reconnect_success_total 1536
telemt_me_reader_eof_total 1426
telemt_me_idle_close_by_peer_total 1426
telemt_me_route_drop_no_conn_total 3662093
telemt_me_route_drop_channel_closed_total 248
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6503286
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1018
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 84
telemt_desync_total 29963
telemt_desync_full_logged_total 10216
telemt_desync_suppressed_total 19747
telemt_desync_frames_bucket_total{bucket="1_2"} 7256
telemt_desync_frames_bucket_total{bucket="3_10"} 11577
telemt_desync_frames_bucket_total{bucket="gt_10"} 11130
telemt_pool_swap_total 146
telemt_pool_force_close_total 4462
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 530
telemt_me_draining_writers_reap_progress_total 45311
telemt_me_writer_removed_unexpected_total 1451
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42394
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40849
telemt_me_writer_teardown_success_total{mode="normal"} 46700
telemt_me_writer_teardown_noop_total 45328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92028
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.984913
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92028
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 530
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6494671
telemt_user_connections_current{user="hello"} 4688
telemt_user_octets_from_client{user="hello"} 160414371987 (149.40 GB)
telemt_user_octets_to_client{user="hello"} 2816131467595 (2.56 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1934
telemt_user_unique_ips_recent_window{user="hello"} 639
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 9202.4 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3927101
telemt_connections_bad_total 255211
telemt_connections_current 6882
telemt_connections_me_current 6882
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 58999
telemt_upstream_connect_attempt_total 22741
telemt_upstream_connect_success_total 21715
telemt_upstream_connect_fail_total 829
telemt_upstream_connect_attempts_per_request{bucket="1"} 22544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4611
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 829
telemt_me_keepalive_timeout_total 415
telemt_me_reconnect_attempts_total 703
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 190
telemt_me_idle_close_by_peer_total 190
telemt_me_route_drop_no_conn_total 8881876
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3270215
telemt_me_endpoint_quarantine_total 69
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 4719
telemt_desync_full_logged_total 1248
telemt_desync_suppressed_total 3471
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 1883
telemt_desync_frames_bucket_total{bucket="gt_10"} 1984
telemt_pool_swap_total 8
telemt_pool_force_close_total 330
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 2405
telemt_me_writer_removed_unexpected_total 279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2183
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2075
telemt_me_writer_teardown_success_total{mode="normal"} 2657
telemt_me_writer_teardown_noop_total 2408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5065
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.727953
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5065
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 3285792
telemt_user_connections_current{user="hello"} 6882
telemt_user_octets_from_client{user="hello"} 18017466002 (16.78 GB)
telemt_user_octets_to_client{user="hello"} 96370304119 (89.75 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2408
telemt_user_unique_ips_recent_window{user="hello"} 1416
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 138929.2 (38h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8363325
telemt_connections_bad_total 728575
telemt_connections_current 4729
telemt_connections_me_current 4729
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 173124
telemt_upstream_connect_attempt_total 86699
telemt_upstream_connect_success_total 85841
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 86579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70675
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 1922
telemt_me_idle_close_by_peer_total 1921
telemt_me_route_drop_no_conn_total 3708418
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6604821
telemt_me_endpoint_quarantine_total 933
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1045
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 33650
telemt_desync_full_logged_total 11584
telemt_desync_suppressed_total 22066
telemt_desync_frames_bucket_total{bucket="1_2"} 6923
telemt_desync_frames_bucket_total{bucket="3_10"} 12901
telemt_desync_frames_bucket_total{bucket="gt_10"} 13826
telemt_pool_swap_total 144
telemt_pool_force_close_total 4191
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 505
telemt_me_draining_writers_reap_progress_total 47838
telemt_me_writer_removed_unexpected_total 1951
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44881
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3651
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 540
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43647
telemt_me_writer_teardown_success_total{mode="normal"} 49814
telemt_me_writer_teardown_noop_total 47839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97653
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.745172
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97653
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 505
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6608025
telemt_user_connections_current{user="hello"} 4729
telemt_user_octets_from_client{user="hello"} 158530828459 (147.64 GB)
telemt_user_octets_to_client{user="hello"} 2605298930325 (2.37 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1716
telemt_user_unique_ips_recent_window{user="hello"} 805
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 75765.3 (21h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7528305
telemt_connections_bad_total 279621
telemt_connections_current 5214
telemt_connections_me_current 5214
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3103625
telemt_upstream_connect_attempt_total 39183
telemt_upstream_connect_success_total 38897
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 39176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_reconnect_attempts_total 47703
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 2395770
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3706666
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 576
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 20089
telemt_desync_full_logged_total 6737
telemt_desync_suppressed_total 13352
telemt_desync_frames_bucket_total{bucket="1_2"} 4074
telemt_desync_frames_bucket_total{bucket="3_10"} 7761
telemt_desync_frames_bucket_total{bucket="gt_10"} 8254
telemt_pool_swap_total 80
telemt_pool_force_close_total 2425
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 240
telemt_me_draining_writers_reap_progress_total 26868
telemt_me_writer_removed_unexpected_total 1072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25564
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 358
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24443
telemt_me_writer_teardown_success_total{mode="normal"} 27965
telemt_me_writer_teardown_noop_total 26875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.322299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 240
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3705242
telemt_user_connections_current{user="hello"} 5214
telemt_user_octets_from_client{user="hello"} 87075913632 (81.10 GB)
telemt_user_octets_to_client{user="hello"} 1496280996986 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2013
telemt_user_unique_ips_recent_window{user="hello"} 704
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 56736.1 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596627
telemt_connections_bad_total 4912
telemt_connections_current 1072
telemt_connections_me_current 1072
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 11128
telemt_upstream_connect_attempt_total 29585
telemt_upstream_connect_success_total 29518
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1284
telemt_me_reconnect_success_total 537
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 196731
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539693
telemt_me_endpoint_quarantine_total 510
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 477
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 9
telemt_desync_total 2927
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 2097
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 1138
telemt_desync_frames_bucket_total{bucket="gt_10"} 1009
telemt_pool_swap_total 59
telemt_pool_force_close_total 1434
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 24084
telemt_me_writer_removed_unexpected_total 511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22825
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22650
telemt_me_writer_teardown_success_total{mode="normal"} 24613
telemt_me_writer_teardown_noop_total 24084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.650707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 541611
telemt_user_connections_current{user="hello"} 1072
telemt_user_octets_from_client{user="hello"} 10371833045 (9.66 GB)
telemt_user_octets_to_client{user="hello"} 254887927323 (237.38 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 138933.7 (38h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10152020
telemt_connections_bad_total 1184134
telemt_connections_current 6020
telemt_connections_me_current 6020
telemt_handshake_timeouts_total 269355
telemt_upstream_connect_attempt_total 53177
telemt_upstream_connect_success_total 52973
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 53130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 2049
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1062
telemt_me_idle_close_by_peer_total 1062
telemt_me_route_drop_no_conn_total 2941332
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7578751
telemt_me_endpoint_quarantine_total 976
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1048
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 30916
telemt_desync_full_logged_total 10167
telemt_desync_suppressed_total 20749
telemt_desync_frames_bucket_total{bucket="1_2"} 7528
telemt_desync_frames_bucket_total{bucket="3_10"} 11326
telemt_desync_frames_bucket_total{bucket="gt_10"} 12062
telemt_pool_swap_total 154
telemt_pool_force_close_total 4183
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 47953
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3881
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45125
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 126
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43770
telemt_me_writer_teardown_success_total{mode="normal"} 49006
telemt_me_writer_teardown_noop_total 47955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.499240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7550390
telemt_user_connections_current{user="hello"} 6020
telemt_user_octets_from_client{user="hello"} 146439469776 (136.38 GB)
telemt_user_octets_to_client{user="hello"} 3503339134644 (3.19 TB)
telemt_user_unique_ips_current{user="hello"} 2065
telemt_user_unique_ips_recent_window{user="hello"} 850
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 138930.2 (38h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8863485
telemt_connections_bad_total 1004251
telemt_connections_current 5196
telemt_connections_me_current 5196
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 226097
telemt_upstream_connect_attempt_total 77697
telemt_upstream_connect_success_total 77141
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 77627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31244
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1969
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_reconnect_attempts_total 6638
telemt_me_reconnect_success_total 1570
telemt_me_reader_eof_total 1394
telemt_me_idle_close_by_peer_total 1394
telemt_me_seq_mismatch_total 66
telemt_me_route_drop_no_conn_total 3301989
telemt_me_route_drop_channel_closed_total 275
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6781638
telemt_me_endpoint_quarantine_total 1082
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1054
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 30150
telemt_desync_full_logged_total 9909
telemt_desync_suppressed_total 20241
telemt_desync_frames_bucket_total{bucket="1_2"} 7436
telemt_desync_frames_bucket_total{bucket="3_10"} 11167
telemt_desync_frames_bucket_total{bucket="gt_10"} 11547
telemt_pool_swap_total 151
telemt_pool_force_close_total 4116
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 46635
telemt_me_writer_removed_unexpected_total 1412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42519
telemt_me_writer_teardown_success_total{mode="normal"} 48111
telemt_me_writer_teardown_noop_total 46639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94750
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.842571
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94750
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1223
telemt_me_writer_restored_fallback_total 90
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6789489
telemt_user_connections_current{user="hello"} 5196
telemt_user_octets_from_client{user="hello"} 122286795625 (113.89 GB)
telemt_user_octets_to_client{user="hello"} 2816216344379 (2.56 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1878
telemt_user_unique_ips_recent_window{user="hello"} 826
```