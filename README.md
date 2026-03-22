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

# Server Metrics 2026-03-22 02:46:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 20386.2 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296487
telemt_connections_bad_total 20196
telemt_connections_current 787
telemt_connections_me_current 787
telemt_handshake_timeouts_total 17165
telemt_upstream_connect_attempt_total 8541
telemt_upstream_connect_success_total 8540
telemt_upstream_connect_attempts_per_request{bucket="1"} 8540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 135
telemt_me_reader_eof_total 130
telemt_me_idle_close_by_peer_total 130
telemt_me_route_drop_no_conn_total 56983
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243539
telemt_me_endpoint_quarantine_total 169
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 49
telemt_desync_total 2154
telemt_desync_full_logged_total 585
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 719
telemt_desync_frames_bucket_total{bucket="3_10"} 797
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 22
telemt_pool_force_close_total 575
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 7699
telemt_me_writer_removed_unexpected_total 130
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 528
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7291
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7124
telemt_me_writer_teardown_success_total{mode="normal"} 7819
telemt_me_writer_teardown_noop_total 7700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15519
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.905585
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15519
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 243063
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 2754515344 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 89510881460 (83.36 GB)
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 33752.0 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793869
telemt_connections_bad_total 48947
telemt_connections_current 390
telemt_connections_me_current 390
telemt_handshake_timeouts_total 29317
telemt_upstream_connect_attempt_total 15679
telemt_upstream_connect_success_total 15429
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 15655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_reconnect_attempts_total 1351
telemt_me_reconnect_success_total 491
telemt_me_reader_eof_total 431
telemt_me_idle_close_by_peer_total 431
telemt_me_route_drop_no_conn_total 341467
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627696
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 275
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_writers_active_current 45
telemt_desync_total 2719
telemt_desync_full_logged_total 1562
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 1105
telemt_pool_swap_total 36
telemt_pool_force_close_total 983
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 13908
telemt_me_writer_removed_unexpected_total 408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13158
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 961
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12925
telemt_me_writer_teardown_success_total{mode="normal"} 14326
telemt_me_writer_teardown_noop_total 13908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28234
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.745235
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28234
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 358
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 626791
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 10238164620 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 223326441696 (207.99 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 108611.9 (30h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7753334
telemt_connections_bad_total 630329
telemt_connections_current 1662
telemt_connections_me_current 1662
telemt_handshake_timeouts_total 254803
telemt_upstream_connect_attempt_total 40283
telemt_upstream_connect_success_total 40209
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1572
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 4537160
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6273089
telemt_me_endpoint_quarantine_total 697
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 814
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26484
telemt_desync_full_logged_total 8761
telemt_desync_suppressed_total 17723
telemt_desync_frames_bucket_total{bucket="1_2"} 5709
telemt_desync_frames_bucket_total{bucket="3_10"} 10347
telemt_desync_frames_bucket_total{bucket="gt_10"} 10428
telemt_pool_swap_total 117
telemt_pool_force_close_total 3891
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 36783
telemt_me_writer_removed_unexpected_total 790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3064
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34043
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32892
telemt_me_writer_teardown_success_total{mode="normal"} 37107
telemt_me_writer_teardown_noop_total 36827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73934
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 159.875095
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73934
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 722
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6265211
telemt_user_connections_current{user="hello"} 1662
telemt_user_octets_from_client{user="hello"} 106367867308 (99.06 GB)
telemt_user_octets_to_client{user="hello"} 2084337398608 (1.90 TB)
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 108613.3 (30h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6401520
telemt_connections_bad_total 587255
telemt_connections_current 1615
telemt_connections_me_current 1615
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 211781
telemt_upstream_connect_attempt_total 44313
telemt_upstream_connect_success_total 43925
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 44116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 556
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1940
telemt_me_reconnect_success_total 870
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 2258128
telemt_me_route_drop_channel_closed_total 261
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4782969
telemt_me_endpoint_quarantine_total 679
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 836
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 46
telemt_desync_total 22587
telemt_desync_full_logged_total 7693
telemt_desync_suppressed_total 14894
telemt_desync_frames_bucket_total{bucket="1_2"} 5434
telemt_desync_frames_bucket_total{bucket="3_10"} 8766
telemt_desync_frames_bucket_total{bucket="gt_10"} 8387
telemt_pool_swap_total 118
telemt_pool_force_close_total 3518
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 35311
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33131
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31793
telemt_me_writer_teardown_success_total{mode="normal"} 36075
telemt_me_writer_teardown_noop_total 35317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.305449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4705120
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 140410053169 (130.77 GB)
telemt_user_octets_to_client{user="hello"} 2221479510955 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 108577.4 (30h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6278156
telemt_connections_bad_total 548001
telemt_connections_current 1506
telemt_connections_me_current 1506
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 203382
telemt_upstream_connect_attempt_total 50443
telemt_upstream_connect_success_total 50073
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1072
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2051
telemt_me_reconnect_success_total 910
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 855
telemt_me_route_drop_no_conn_total 2151560
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4672095
telemt_me_endpoint_quarantine_total 758
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 812
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 22504
telemt_desync_full_logged_total 7567
telemt_desync_suppressed_total 14937
telemt_desync_frames_bucket_total{bucket="1_2"} 5496
telemt_desync_frames_bucket_total{bucket="3_10"} 8620
telemt_desync_frames_bucket_total{bucket="gt_10"} 8388
telemt_pool_swap_total 117
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 36429
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34248
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33026
telemt_me_writer_teardown_success_total{mode="normal"} 37270
telemt_me_writer_teardown_noop_total 36441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.048776
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 4667697
telemt_user_connections_current{user="hello"} 1506
telemt_user_octets_from_client{user="hello"} 133736278419 (124.55 GB)
telemt_user_octets_to_client{user="hello"} 2136747748015 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 108616.5 (30h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20423235
telemt_connections_bad_total 1624705
telemt_connections_current 2191
telemt_connections_me_current 2191
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 607236
telemt_upstream_connect_attempt_total 199374
telemt_upstream_connect_success_total 181279
telemt_upstream_connect_fail_total 16338
telemt_upstream_connect_attempts_per_request{bucket="1"} 197617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8929
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16338
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64902
telemt_me_reconnect_success_total 2329
telemt_me_reader_eof_total 1459
telemt_me_idle_close_by_peer_total 1458
telemt_me_route_drop_no_conn_total 39509931
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16504762
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 855
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 850
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_desync_total 31952
telemt_desync_full_logged_total 9586
telemt_desync_suppressed_total 22366
telemt_desync_frames_bucket_total{bucket="1_2"} 6924
telemt_desync_frames_bucket_total{bucket="3_10"} 14182
telemt_desync_frames_bucket_total{bucket="gt_10"} 10846
telemt_pool_swap_total 112
telemt_pool_force_close_total 3626
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 794
telemt_me_draining_writers_reap_progress_total 34073
telemt_me_writer_removed_unexpected_total 2157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31364
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30447
telemt_me_writer_teardown_success_total{mode="normal"} 35971
telemt_me_writer_teardown_noop_total 34099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.680167
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 794
telemt_me_refill_failed_total 3802
telemt_me_writer_restored_same_endpoint_total 1597
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 16637923
telemt_user_connections_current{user="hello"} 2191
telemt_user_octets_from_client{user="hello"} 219462316308 (204.39 GB)
telemt_user_octets_to_client{user="hello"} 1202414895013 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 108584.2 (30h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6033398
telemt_connections_bad_total 568456
telemt_connections_current 1603
telemt_connections_me_current 1603
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 126860
telemt_upstream_connect_attempt_total 59067
telemt_upstream_connect_success_total 58388
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 58970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_reconnect_attempts_total 69653
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1568
telemt_me_idle_close_by_peer_total 1567
telemt_me_route_drop_no_conn_total 2389853
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4703647
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 824
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 45
telemt_desync_total 23376
telemt_desync_full_logged_total 8236
telemt_desync_suppressed_total 15140
telemt_desync_frames_bucket_total{bucket="1_2"} 4452
telemt_desync_frames_bucket_total{bucket="3_10"} 9051
telemt_desync_frames_bucket_total{bucket="gt_10"} 9873
telemt_pool_swap_total 112
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 38253
telemt_me_writer_removed_unexpected_total 1606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3928
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35962
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2822
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35030
telemt_me_writer_teardown_success_total{mode="normal"} 39890
telemt_me_writer_teardown_noop_total 38254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78144
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.125524
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78144
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1500
telemt_me_writer_restored_fallback_total 34
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4696448
telemt_user_connections_current{user="hello"} 1603
telemt_user_octets_from_client{user="hello"} 124496636052 (115.95 GB)
telemt_user_octets_to_client{user="hello"} 1915286161454 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 812
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 45420.1 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3934479
telemt_connections_bad_total 144607
telemt_connections_current 1291
telemt_connections_me_current 1291
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1603786
telemt_upstream_connect_attempt_total 27638
telemt_upstream_connect_success_total 27461
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 27631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 45819
telemt_me_reconnect_success_total 967
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 649
telemt_me_route_drop_no_conn_total 1022737
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1928479
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 350
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10462
telemt_desync_full_logged_total 3609
telemt_desync_suppressed_total 6853
telemt_desync_frames_bucket_total{bucket="1_2"} 1876
telemt_desync_frames_bucket_total{bucket="3_10"} 4012
telemt_desync_frames_bucket_total{bucket="gt_10"} 4574
telemt_pool_swap_total 49
telemt_pool_force_close_total 1492
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 16685
telemt_me_writer_removed_unexpected_total 723
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1528
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15906
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1286
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15193
telemt_me_writer_teardown_success_total{mode="normal"} 17434
telemt_me_writer_teardown_noop_total 16687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34121
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.443025
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34121
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 866
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1932078
telemt_user_connections_current{user="hello"} 1291
telemt_user_octets_from_client{user="hello"} 54095350908 (50.38 GB)
telemt_user_octets_to_client{user="hello"} 821353717250 (764.95 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 26391.1 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197452
telemt_connections_bad_total 1681
telemt_connections_current 270
telemt_connections_me_current 270
telemt_handshake_timeouts_total 5429
telemt_upstream_connect_attempt_total 12740
telemt_upstream_connect_success_total 12708
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 12738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 285
telemt_me_reconnect_success_total 164
telemt_me_reader_eof_total 168
telemt_me_idle_close_by_peer_total 168
telemt_me_route_drop_no_conn_total 54241
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174022
telemt_me_endpoint_quarantine_total 262
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 45
telemt_desync_total 1026
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 29
telemt_pool_force_close_total 647
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 11486
telemt_me_writer_removed_unexpected_total 161
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 745
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10909
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 645
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10839
telemt_me_writer_teardown_success_total{mode="normal"} 11654
telemt_me_writer_teardown_noop_total 11486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23140
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.981661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23140
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 148
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 173707
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 3099699748 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 107145362476 (99.79 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 108588.8 (30h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7345013
telemt_connections_bad_total 742299
telemt_connections_current 1769
telemt_connections_me_current 1769
telemt_handshake_timeouts_total 209383
telemt_upstream_connect_attempt_total 42567
telemt_upstream_connect_success_total 42410
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 42530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 1586
telemt_me_reconnect_success_total 852
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 835
telemt_me_route_drop_no_conn_total 2127997
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5487059
telemt_me_endpoint_quarantine_total 763
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 838
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21490
telemt_desync_full_logged_total 7052
telemt_desync_suppressed_total 14438
telemt_desync_frames_bucket_total{bucket="1_2"} 5408
telemt_desync_frames_bucket_total{bucket="3_10"} 7764
telemt_desync_frames_bucket_total{bucket="gt_10"} 8318
telemt_pool_swap_total 120
telemt_pool_force_close_total 3213
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 38390
telemt_me_writer_removed_unexpected_total 806
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3017
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35177
telemt_me_writer_teardown_success_total{mode="normal"} 39215
telemt_me_writer_teardown_noop_total 38392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77607
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.645703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77607
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 762
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5462085
telemt_user_connections_current{user="hello"} 1769
telemt_user_octets_from_client{user="hello"} 109655130004 (102.12 GB)
telemt_user_octets_to_client{user="hello"} 2544430527092 (2.31 TB)
telemt_user_unique_ips_current{user="hello"} 786
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 108585.3 (30h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6336164
telemt_connections_bad_total 626243
telemt_connections_current 1663
telemt_connections_me_current 1663
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172821
telemt_upstream_connect_attempt_total 58357
telemt_upstream_connect_success_total 57919
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 58298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_reconnect_attempts_total 5573
telemt_me_reconnect_success_total 1175
telemt_me_reader_eof_total 1061
telemt_me_idle_close_by_peer_total 1061
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 2180726
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4853727
telemt_me_endpoint_quarantine_total 859
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 832
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 20141
telemt_desync_full_logged_total 6704
telemt_desync_suppressed_total 13437
telemt_desync_frames_bucket_total{bucket="1_2"} 5160
telemt_desync_frames_bucket_total{bucket="3_10"} 7339
telemt_desync_frames_bucket_total{bucket="gt_10"} 7642
telemt_pool_swap_total 118
telemt_pool_force_close_total 3174
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 36948
telemt_me_writer_removed_unexpected_total 1071
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3546
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34526
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33774
telemt_me_writer_teardown_success_total{mode="normal"} 38072
telemt_me_writer_teardown_noop_total 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75024
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.085236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75024
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 918
telemt_me_writer_restored_fallback_total 63
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4856748
telemt_user_connections_current{user="hello"} 1663
telemt_user_octets_from_client{user="hello"} 91581024217 (85.29 GB)
telemt_user_octets_to_client{user="hello"} 2074288474600 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 776
telemt_user_unique_ips_recent_window{user="hello"} 148
```