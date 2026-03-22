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

# Server Metrics 2026-03-22 03:01:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 21301.1 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313341
telemt_connections_bad_total 21137
telemt_connections_current 921
telemt_connections_me_current 921
telemt_handshake_timeouts_total 18016
telemt_upstream_connect_attempt_total 8944
telemt_upstream_connect_success_total 8943
telemt_upstream_connect_attempts_per_request{bucket="1"} 8943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 268
telemt_me_reconnect_success_total 143
telemt_me_reader_eof_total 138
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 59606
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257719
telemt_me_endpoint_quarantine_total 174
telemt_me_single_endpoint_shadow_rotate_total 179
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
telemt_me_writers_active_current 43
telemt_desync_total 2256
telemt_desync_full_logged_total 614
telemt_desync_suppressed_total 1642
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 841
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 23
telemt_pool_force_close_total 604
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 8054
telemt_me_writer_removed_unexpected_total 138
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7637
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7450
telemt_me_writer_teardown_success_total{mode="normal"} 8182
telemt_me_writer_teardown_noop_total 8055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16237
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.928187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16237
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 257208
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 2937304072 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 93800598216 (87.36 GB)
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 34667.5 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804973
telemt_connections_bad_total 51115
telemt_connections_current 510
telemt_connections_me_current 510
telemt_handshake_timeouts_total 29717
telemt_upstream_connect_attempt_total 16158
telemt_upstream_connect_success_total 15905
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 16135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_reconnect_attempts_total 1360
telemt_me_reconnect_success_total 498
telemt_me_reader_eof_total 438
telemt_me_idle_close_by_peer_total 438
telemt_me_route_drop_no_conn_total 343051
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 635834
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 281
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 2751
telemt_desync_full_logged_total 1581
telemt_desync_suppressed_total 1170
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 1050
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 37
telemt_pool_force_close_total 1004
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 14332
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1202
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13555
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13328
telemt_me_writer_teardown_success_total{mode="normal"} 14757
telemt_me_writer_teardown_noop_total 14332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29089
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.763415
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29089
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 634912
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 10310587960 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 225964424648 (210.45 GB)
telemt_user_unique_ips_current{user="hello"} 382
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 109527.4 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7783451
telemt_connections_bad_total 633708
telemt_connections_current 1849
telemt_connections_me_current 1849
telemt_handshake_timeouts_total 255762
telemt_upstream_connect_attempt_total 40707
telemt_upstream_connect_success_total 40632
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1583
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 830
telemt_me_idle_close_by_peer_total 830
telemt_me_route_drop_no_conn_total 4541481
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6296216
telemt_me_endpoint_quarantine_total 702
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 820
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
telemt_me_writers_active_current 43
telemt_desync_total 26526
telemt_desync_full_logged_total 8782
telemt_desync_suppressed_total 17744
telemt_desync_frames_bucket_total{bucket="1_2"} 5717
telemt_desync_frames_bucket_total{bucket="3_10"} 10364
telemt_desync_frames_bucket_total{bucket="gt_10"} 10445
telemt_pool_swap_total 118
telemt_pool_force_close_total 3912
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 605
telemt_me_draining_writers_reap_progress_total 37145
telemt_me_writer_removed_unexpected_total 799
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3101
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34377
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33233
telemt_me_writer_teardown_success_total{mode="normal"} 37478
telemt_me_writer_teardown_noop_total 37189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74667
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 160.776014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74667
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 605
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6288315
telemt_user_connections_current{user="hello"} 1849
telemt_user_octets_from_client{user="hello"} 107216861380 (99.85 GB)
telemt_user_octets_to_client{user="hello"} 2094264868684 (1.90 TB)
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 109528.8 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6427882
telemt_connections_bad_total 588828
telemt_connections_current 1685
telemt_connections_me_current 1685
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 213087
telemt_upstream_connect_attempt_total 44741
telemt_upstream_connect_success_total 44351
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 44544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1950
telemt_me_reconnect_success_total 881
telemt_me_reader_eof_total 852
telemt_me_idle_close_by_peer_total 852
telemt_me_route_drop_no_conn_total 2261836
telemt_me_route_drop_channel_closed_total 263
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4801512
telemt_me_endpoint_quarantine_total 688
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 844
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22671
telemt_desync_full_logged_total 7725
telemt_desync_suppressed_total 14946
telemt_desync_frames_bucket_total{bucket="1_2"} 5457
telemt_desync_frames_bucket_total{bucket="3_10"} 8804
telemt_desync_frames_bucket_total{bucket="gt_10"} 8410
telemt_pool_swap_total 119
telemt_pool_force_close_total 3544
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 35675
telemt_me_writer_removed_unexpected_total 837
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2973
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33476
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32131
telemt_me_writer_teardown_success_total{mode="normal"} 36449
telemt_me_writer_teardown_noop_total 35681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72130
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.322906
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72130
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 771
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4723647
telemt_user_connections_current{user="hello"} 1685
telemt_user_octets_from_client{user="hello"} 140650723853 (130.99 GB)
telemt_user_octets_to_client{user="hello"} 2231530433455 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 844
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 109493.1 (30h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6308640
telemt_connections_bad_total 549094
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 204388
telemt_upstream_connect_attempt_total 50828
telemt_upstream_connect_success_total 50456
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1076
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2071
telemt_me_reconnect_success_total 913
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 2155762
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4690169
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 818
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
telemt_me_writers_active_current 45
telemt_desync_total 22587
telemt_desync_full_logged_total 7601
telemt_desync_suppressed_total 14986
telemt_desync_frames_bucket_total{bucket="1_2"} 5509
telemt_desync_frames_bucket_total{bucket="3_10"} 8653
telemt_desync_frames_bucket_total{bucket="gt_10"} 8425
telemt_pool_swap_total 118
telemt_pool_force_close_total 3426
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 36785
telemt_me_writer_removed_unexpected_total 830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3042
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33359
telemt_me_writer_teardown_success_total{mode="normal"} 37629
telemt_me_writer_teardown_noop_total 36797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74426
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.069125
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74426
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4685690
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 134023009075 (124.82 GB)
telemt_user_octets_to_client{user="hello"} 2147537417515 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 744
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 109532.2 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20469318
telemt_connections_bad_total 1638845
telemt_connections_current 2533
telemt_connections_me_current 2533
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 611268
telemt_upstream_connect_attempt_total 199709
telemt_upstream_connect_success_total 181606
telemt_upstream_connect_fail_total 16340
telemt_upstream_connect_attempts_per_request{bucket="1"} 197946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8930
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16340
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64942
telemt_me_reconnect_success_total 2334
telemt_me_reader_eof_total 1464
telemt_me_idle_close_by_peer_total 1463
telemt_me_route_drop_no_conn_total 39517700
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16531645
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 859
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 859
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
telemt_me_writers_active_current 43
telemt_desync_total 32009
telemt_desync_full_logged_total 9615
telemt_desync_suppressed_total 22394
telemt_desync_frames_bucket_total{bucket="1_2"} 6932
telemt_desync_frames_bucket_total{bucket="3_10"} 14213
telemt_desync_frames_bucket_total{bucket="gt_10"} 10864
telemt_pool_swap_total 113
telemt_pool_force_close_total 3656
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 798
telemt_me_draining_writers_reap_progress_total 34386
telemt_me_writer_removed_unexpected_total 2162
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4629
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31660
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3132
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 524
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30730
telemt_me_writer_teardown_success_total{mode="normal"} 36289
telemt_me_writer_teardown_noop_total 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70702
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.171787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70702
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 798
telemt_me_refill_failed_total 3804
telemt_me_writer_restored_same_endpoint_total 1599
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 16664794
telemt_user_connections_current{user="hello"} 2533
telemt_user_octets_from_client{user="hello"} 222684783300 (207.39 GB)
telemt_user_octets_to_client{user="hello"} 1212136793205 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1149
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 109499.6 (30h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6057625
telemt_connections_bad_total 571355
telemt_connections_current 1764
telemt_connections_me_current 1764
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 127392
telemt_upstream_connect_attempt_total 59483
telemt_upstream_connect_success_total 58794
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 59382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_reconnect_attempts_total 69673
telemt_me_reconnect_success_total 1804
telemt_me_reader_eof_total 1583
telemt_me_idle_close_by_peer_total 1582
telemt_me_route_drop_no_conn_total 2393374
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4720522
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 830
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
telemt_desync_total 23459
telemt_desync_full_logged_total 8271
telemt_desync_suppressed_total 15188
telemt_desync_frames_bucket_total{bucket="1_2"} 4481
telemt_desync_frames_bucket_total{bucket="3_10"} 9085
telemt_desync_frames_bucket_total{bucket="gt_10"} 9893
telemt_pool_swap_total 113
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 38625
telemt_me_writer_removed_unexpected_total 1621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3964
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36313
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35379
telemt_me_writer_teardown_success_total{mode="normal"} 40277
telemt_me_writer_teardown_noop_total 38626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.130616
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1513
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 4713293
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 125029431216 (116.44 GB)
telemt_user_octets_to_client{user="hello"} 1921335420762 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 873
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 46335.5 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3971598
telemt_connections_bad_total 147856
telemt_connections_current 1508
telemt_connections_me_current 1508
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1616807
telemt_upstream_connect_attempt_total 28113
telemt_upstream_connect_success_total 27934
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 28106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_reconnect_attempts_total 45833
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 662
telemt_me_idle_close_by_peer_total 662
telemt_me_route_drop_no_conn_total 1025404
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1945296
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 358
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10525
telemt_desync_full_logged_total 3629
telemt_desync_suppressed_total 6896
telemt_desync_frames_bucket_total{bucket="1_2"} 1901
telemt_desync_frames_bucket_total{bucket="3_10"} 4033
telemt_desync_frames_bucket_total{bucket="gt_10"} 4591
telemt_pool_swap_total 50
telemt_pool_force_close_total 1509
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 17086
telemt_me_writer_removed_unexpected_total 735
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1553
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16295
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15577
telemt_me_writer_teardown_success_total{mode="normal"} 17848
telemt_me_writer_teardown_noop_total 17088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34936
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.490259
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34936
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 877
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1948869
telemt_user_connections_current{user="hello"} 1508
telemt_user_octets_from_client{user="hello"} 54378303972 (50.64 GB)
telemt_user_octets_to_client{user="hello"} 826513197286 (769.75 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 27306.4 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201168
telemt_connections_bad_total 1742
telemt_connections_current 377
telemt_connections_me_current 377
telemt_handshake_timeouts_total 5522
telemt_upstream_connect_attempt_total 13211
telemt_upstream_connect_success_total 13179
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 292
telemt_me_reconnect_success_total 170
telemt_me_reader_eof_total 175
telemt_me_idle_close_by_peer_total 175
telemt_me_route_drop_no_conn_total 55349
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177407
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_shadow_rotate_total 240
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 1031
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 30
telemt_pool_force_close_total 669
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 11936
telemt_me_writer_removed_unexpected_total 168
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11347
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 667
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11267
telemt_me_writer_teardown_success_total{mode="normal"} 12111
telemt_me_writer_teardown_noop_total 11936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24047
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.033343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24047
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 177090
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 3159116496 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 109588008036 (102.06 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 109504.1 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7372982
telemt_connections_bad_total 743524
telemt_connections_current 1942
telemt_connections_me_current 1942
telemt_handshake_timeouts_total 210066
telemt_upstream_connect_attempt_total 42978
telemt_upstream_connect_success_total 42821
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 42941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 1589
telemt_me_reconnect_success_total 854
telemt_me_reader_eof_total 837
telemt_me_idle_close_by_peer_total 837
telemt_me_route_drop_no_conn_total 2131383
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5505099
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 845
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
telemt_me_writers_active_current 46
telemt_desync_total 21601
telemt_desync_full_logged_total 7077
telemt_desync_suppressed_total 14524
telemt_desync_frames_bucket_total{bucket="1_2"} 5431
telemt_desync_frames_bucket_total{bucket="3_10"} 7816
telemt_desync_frames_bucket_total{bucket="gt_10"} 8354
telemt_pool_swap_total 121
telemt_pool_force_close_total 3236
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 38761
telemt_me_writer_removed_unexpected_total 808
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36549
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35525
telemt_me_writer_teardown_success_total{mode="normal"} 39588
telemt_me_writer_teardown_noop_total 38763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78351
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.673876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78351
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 764
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5480105
telemt_user_connections_current{user="hello"} 1942
telemt_user_octets_from_client{user="hello"} 109912801556 (102.36 GB)
telemt_user_octets_to_client{user="hello"} 2552232427236 (2.32 TB)
telemt_user_unique_ips_current{user="hello"} 839
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 109500.6 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6368228
telemt_connections_bad_total 629446
telemt_connections_current 1755
telemt_connections_me_current 1755
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 173661
telemt_upstream_connect_attempt_total 58779
telemt_upstream_connect_success_total 58339
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 58720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_reconnect_attempts_total 5585
telemt_me_reconnect_success_total 1185
telemt_me_reader_eof_total 1071
telemt_me_idle_close_by_peer_total 1071
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 2184523
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4872116
telemt_me_endpoint_quarantine_total 864
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 839
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
telemt_desync_total 20214
telemt_desync_full_logged_total 6733
telemt_desync_suppressed_total 13481
telemt_desync_frames_bucket_total{bucket="1_2"} 5179
telemt_desync_frames_bucket_total{bucket="3_10"} 7370
telemt_desync_frames_bucket_total{bucket="gt_10"} 7665
telemt_pool_swap_total 119
telemt_pool_force_close_total 3195
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 382
telemt_me_draining_writers_reap_progress_total 37318
telemt_me_writer_removed_unexpected_total 1081
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3567
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34885
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34123
telemt_me_writer_teardown_success_total{mode="normal"} 38452
telemt_me_writer_teardown_noop_total 37322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75774
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.092883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75774
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 382
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 927
telemt_me_writer_restored_fallback_total 64
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4875107
telemt_user_connections_current{user="hello"} 1755
telemt_user_octets_from_client{user="hello"} 91975685537 (85.66 GB)
telemt_user_octets_to_client{user="hello"} 2083061495532 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 817
telemt_user_unique_ips_recent_window{user="hello"} 221
```