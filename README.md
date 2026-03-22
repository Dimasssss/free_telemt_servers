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

# Server Metrics 2026-03-22 04:18:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 25897.5 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410805
telemt_connections_bad_total 26007
telemt_connections_current 982
telemt_connections_me_current 982
telemt_handshake_timeouts_total 23222
telemt_upstream_connect_attempt_total 10853
telemt_upstream_connect_success_total 10852
telemt_upstream_connect_attempts_per_request{bucket="1"} 10852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 296
telemt_me_reconnect_success_total 169
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 84137
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339610
telemt_me_endpoint_quarantine_total 205
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 3055
telemt_desync_full_logged_total 835
telemt_desync_suppressed_total 2220
telemt_desync_frames_bucket_total{bucket="1_2"} 1057
telemt_desync_frames_bucket_total{bucket="3_10"} 1155
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 28
telemt_pool_force_close_total 734
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 9801
telemt_me_writer_removed_unexpected_total 163
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9303
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 729
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9067
telemt_me_writer_teardown_success_total{mode="normal"} 9956
telemt_me_writer_teardown_noop_total 9802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19758
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.585850
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19758
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 152
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 338688
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 4236513704 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 118068801048 (109.96 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 39263.8 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869046
telemt_connections_bad_total 58035
telemt_connections_current 668
telemt_connections_me_current 668
telemt_handshake_timeouts_total 31131
telemt_upstream_connect_attempt_total 18405
telemt_upstream_connect_success_total 18120
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 18378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 1508
telemt_me_reconnect_success_total 558
telemt_me_reader_eof_total 495
telemt_me_idle_close_by_peer_total 495
telemt_me_route_drop_no_conn_total 355338
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688862
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 319
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 2945
telemt_desync_full_logged_total 1688
telemt_desync_suppressed_total 1257
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 1131
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 42
telemt_pool_force_close_total 1124
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 16332
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1351
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15463
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15208
telemt_me_writer_teardown_success_total{mode="normal"} 16814
telemt_me_writer_teardown_noop_total 16332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33146
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.908083
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33146
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 416
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 687805
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 11081908692 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 247907620804 (230.88 GB)
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 114123.8 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7974645
telemt_connections_bad_total 667466
telemt_connections_current 2345
telemt_connections_me_current 2345
telemt_handshake_timeouts_total 262125
telemt_upstream_connect_attempt_total 42604
telemt_upstream_connect_success_total 42526
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 42534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1632
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 4576596
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6436518
telemt_me_endpoint_quarantine_total 737
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 855
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 44
telemt_desync_total 26985
telemt_desync_full_logged_total 8961
telemt_desync_suppressed_total 18024
telemt_desync_frames_bucket_total{bucket="1_2"} 5836
telemt_desync_frames_bucket_total{bucket="3_10"} 10547
telemt_desync_frames_bucket_total{bucket="gt_10"} 10602
telemt_pool_swap_total 123
telemt_pool_force_close_total 4046
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 614
telemt_me_draining_writers_reap_progress_total 38875
telemt_me_writer_removed_unexpected_total 826
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36006
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3806
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34829
telemt_me_writer_teardown_success_total{mode="normal"} 39236
telemt_me_writer_teardown_noop_total 38919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78155
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.447624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78155
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 614
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 757
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6428318
telemt_user_connections_current{user="hello"} 2345
telemt_user_octets_from_client{user="hello"} 109327145336 (101.82 GB)
telemt_user_octets_to_client{user="hello"} 2158769558564 (1.96 TB)
telemt_user_unique_ips_current{user="hello"} 1063
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 114125.2 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6594420
telemt_connections_bad_total 594223
telemt_connections_current 2348
telemt_connections_me_current 2348
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 218757
telemt_upstream_connect_attempt_total 46544
telemt_upstream_connect_success_total 46148
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 46347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1975
telemt_me_reconnect_success_total 904
telemt_me_reader_eof_total 878
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 2290225
telemt_me_route_drop_channel_closed_total 279
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4920760
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 881
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
telemt_me_writers_active_current 44
telemt_desync_total 23029
telemt_desync_full_logged_total 7865
telemt_desync_suppressed_total 15164
telemt_desync_frames_bucket_total{bucket="1_2"} 5535
telemt_desync_frames_bucket_total{bucket="3_10"} 8948
telemt_desync_frames_bucket_total{bucket="gt_10"} 8546
telemt_pool_swap_total 124
telemt_pool_force_close_total 3678
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 37328
telemt_me_writer_removed_unexpected_total 860
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35044
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3461
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33650
telemt_me_writer_teardown_success_total{mode="normal"} 38128
telemt_me_writer_teardown_noop_total 37334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75462
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.507984
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75462
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4842447
telemt_user_connections_current{user="hello"} 2348
telemt_user_octets_from_client{user="hello"} 143226417449 (133.39 GB)
telemt_user_octets_to_client{user="hello"} 2305685605399 (2.10 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1065
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 114092.6 (31h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6457022
telemt_connections_bad_total 552181
telemt_connections_current 1829
telemt_connections_me_current 1829
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 212890
telemt_upstream_connect_attempt_total 53008
telemt_upstream_connect_success_total 52518
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 52660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 1021
telemt_me_reader_eof_total 961
telemt_me_idle_close_by_peer_total 961
telemt_me_route_drop_no_conn_total 2244126
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4798399
telemt_me_endpoint_quarantine_total 808
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 850
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
telemt_me_writers_active_current 44
telemt_desync_total 22929
telemt_desync_full_logged_total 7753
telemt_desync_suppressed_total 15176
telemt_desync_frames_bucket_total{bucket="1_2"} 5599
telemt_desync_frames_bucket_total{bucket="3_10"} 8792
telemt_desync_frames_bucket_total{bucket="gt_10"} 8538
telemt_pool_swap_total 122
telemt_pool_force_close_total 3553
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 38527
telemt_me_writer_removed_unexpected_total 948
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36229
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34974
telemt_me_writer_teardown_success_total{mode="normal"} 39493
telemt_me_writer_teardown_noop_total 38539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.269771
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 894
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 4793343
telemt_user_connections_current{user="hello"} 1829
telemt_user_octets_from_client{user="hello"} 135499003055 (126.19 GB)
telemt_user_octets_to_client{user="hello"} 2193504135319 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 853
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 114128.4 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20754031
telemt_connections_bad_total 1719552
telemt_connections_current 3006
telemt_connections_me_current 3006
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 627938
telemt_upstream_connect_attempt_total 203357
telemt_upstream_connect_success_total 185065
telemt_upstream_connect_fail_total 16470
telemt_upstream_connect_attempts_per_request{bucket="1"} 201535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8950
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16470
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65151
telemt_me_reconnect_success_total 2418
telemt_me_reader_eof_total 1502
telemt_me_idle_close_by_peer_total 1501
telemt_me_route_drop_no_conn_total 39584736
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16708790
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 887
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 895
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32352
telemt_desync_full_logged_total 9741
telemt_desync_suppressed_total 22611
telemt_desync_frames_bucket_total{bucket="1_2"} 7033
telemt_desync_frames_bucket_total{bucket="3_10"} 14346
telemt_desync_frames_bucket_total{bucket="gt_10"} 10973
telemt_pool_swap_total 118
telemt_pool_force_close_total 3803
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 832
telemt_me_draining_writers_reap_progress_total 35797
telemt_me_writer_removed_unexpected_total 2242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32968
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3272
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 531
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31994
telemt_me_writer_teardown_success_total{mode="normal"} 37783
telemt_me_writer_teardown_noop_total 35824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73607
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.950470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73607
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 832
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1641
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 16843528
telemt_user_connections_current{user="hello"} 3006
telemt_user_octets_from_client{user="hello"} 237523243692 (221.21 GB)
telemt_user_octets_to_client{user="hello"} 1272722825051 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1303
telemt_user_unique_ips_recent_window{user="hello"} 394
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 114096.0 (31h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6231270
telemt_connections_bad_total 603276
telemt_connections_current 2227
telemt_connections_me_current 2227
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 131331
telemt_upstream_connect_attempt_total 61382
telemt_upstream_connect_success_total 60685
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 61280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_reconnect_attempts_total 69830
telemt_me_reconnect_success_total 1837
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 2421492
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4832348
telemt_me_endpoint_quarantine_total 774
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 868
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24147
telemt_desync_full_logged_total 8463
telemt_desync_suppressed_total 15684
telemt_desync_frames_bucket_total{bucket="1_2"} 4730
telemt_desync_frames_bucket_total{bucket="3_10"} 9335
telemt_desync_frames_bucket_total{bucket="gt_10"} 10082
telemt_pool_swap_total 118
telemt_pool_force_close_total 3374
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 40341
telemt_me_writer_removed_unexpected_total 1656
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4100
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37930
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2973
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36967
telemt_me_writer_teardown_success_total{mode="normal"} 42030
telemt_me_writer_teardown_noop_total 40342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.344648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1541
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4824771
telemt_user_connections_current{user="hello"} 2227
telemt_user_octets_from_client{user="hello"} 126735144028 (118.03 GB)
telemt_user_octets_to_client{user="hello"} 1986374805090 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1036
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 50931.8 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4173038
telemt_connections_bad_total 177133
telemt_connections_current 1725
telemt_connections_me_current 1725
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1674114
telemt_upstream_connect_attempt_total 30255
telemt_upstream_connect_success_total 30058
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 30248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_reconnect_attempts_total 45972
telemt_me_reconnect_success_total 1009
telemt_me_reader_eof_total 696
telemt_me_idle_close_by_peer_total 696
telemt_me_route_drop_no_conn_total 1048930
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2044659
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 396
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10981
telemt_desync_full_logged_total 3794
telemt_desync_suppressed_total 7187
telemt_desync_frames_bucket_total{bucket="1_2"} 2038
telemt_desync_frames_bucket_total{bucket="3_10"} 4215
telemt_desync_frames_bucket_total{bucket="gt_10"} 4728
telemt_pool_swap_total 55
telemt_pool_force_close_total 1620
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 19042
telemt_me_writer_removed_unexpected_total 768
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17422
telemt_me_writer_teardown_success_total{mode="normal"} 19838
telemt_me_writer_teardown_noop_total 19044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.511740
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 902
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2048085
telemt_user_connections_current{user="hello"} 1725
telemt_user_octets_from_client{user="hello"} 55891787348 (52.05 GB)
telemt_user_octets_to_client{user="hello"} 879303762854 (818.92 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 31902.6 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225848
telemt_connections_bad_total 1832
telemt_connections_current 363
telemt_connections_me_current 363
telemt_handshake_timeouts_total 5971
telemt_upstream_connect_attempt_total 15471
telemt_upstream_connect_success_total 15435
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 343
telemt_me_reconnect_success_total 200
telemt_me_reader_eof_total 204
telemt_me_idle_close_by_peer_total 204
telemt_me_route_drop_no_conn_total 62591
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200036
telemt_me_endpoint_quarantine_total 309
telemt_me_single_endpoint_shadow_rotate_total 279
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1138
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 835
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 432
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 35
telemt_pool_force_close_total 781
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 14008
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 881
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13331
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13227
telemt_me_writer_teardown_success_total{mode="normal"} 14212
telemt_me_writer_teardown_noop_total 14008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.110863
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 181
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 199693
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 3468560816 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 120655499308 (112.37 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 114100.4 (31h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7545954
telemt_connections_bad_total 758330
telemt_connections_current 2345
telemt_connections_me_current 2345
telemt_handshake_timeouts_total 215227
telemt_upstream_connect_attempt_total 45000
telemt_upstream_connect_success_total 44837
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 44963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_reconnect_attempts_total 1649
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 2159067
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5624832
telemt_me_endpoint_quarantine_total 816
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 877
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
telemt_me_writers_active_current 45
telemt_desync_total 22047
telemt_desync_full_logged_total 7247
telemt_desync_suppressed_total 14800
telemt_desync_frames_bucket_total{bucket="1_2"} 5522
telemt_desync_frames_bucket_total{bucket="3_10"} 8001
telemt_desync_frames_bucket_total{bucket="gt_10"} 8524
telemt_pool_swap_total 126
telemt_pool_force_close_total 3361
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 398
telemt_me_draining_writers_reap_progress_total 40613
telemt_me_writer_removed_unexpected_total 837
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38309
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37252
telemt_me_writer_teardown_success_total{mode="normal"} 41474
telemt_me_writer_teardown_noop_total 40615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82089
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.729828
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82089
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 398
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 790
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5599675
telemt_user_connections_current{user="hello"} 2345
telemt_user_octets_from_client{user="hello"} 111348980012 (103.70 GB)
telemt_user_octets_to_client{user="hello"} 2609422181980 (2.37 TB)
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 114097.0 (31h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6541172
telemt_connections_bad_total 641618
telemt_connections_current 2173
telemt_connections_me_current 2173
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 176738
telemt_upstream_connect_attempt_total 60797
telemt_upstream_connect_success_total 60339
telemt_upstream_connect_fail_total 398
telemt_upstream_connect_attempts_per_request{bucket="1"} 60737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 398
telemt_me_reconnect_attempts_total 5688
telemt_me_reconnect_success_total 1231
telemt_me_reader_eof_total 1113
telemt_me_idle_close_by_peer_total 1113
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2211250
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4991792
telemt_me_endpoint_quarantine_total 897
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 874
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
telemt_me_writers_active_current 43
telemt_desync_total 20691
telemt_desync_full_logged_total 6904
telemt_desync_suppressed_total 13787
telemt_desync_frames_bucket_total{bucket="1_2"} 5273
telemt_desync_frames_bucket_total{bucket="3_10"} 7574
telemt_desync_frames_bucket_total{bucket="gt_10"} 7844
telemt_pool_swap_total 124
telemt_pool_force_close_total 3311
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 39148
telemt_me_writer_removed_unexpected_total 1124
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3711
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36617
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3088
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35837
telemt_me_writer_teardown_success_total{mode="normal"} 40328
telemt_me_writer_teardown_noop_total 39152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79480
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.301325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79480
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 961
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 4994619
telemt_user_connections_current{user="hello"} 2173
telemt_user_octets_from_client{user="hello"} 94305065501 (87.83 GB)
telemt_user_octets_to_client{user="hello"} 2138287924692 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 976
telemt_user_unique_ips_recent_window{user="hello"} 246
```