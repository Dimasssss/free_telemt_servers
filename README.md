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

# Server Metrics 2026-03-22 15:53:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67651.2 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2371916
telemt_connections_bad_total 127426
telemt_connections_current 1684
telemt_connections_me_current 1684
telemt_handshake_timeouts_total 86482
telemt_upstream_connect_attempt_total 25056
telemt_upstream_connect_success_total 25055
telemt_upstream_connect_attempts_per_request{bucket="1"} 25055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1022
telemt_me_reconnect_success_total 430
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 432
telemt_me_route_drop_no_conn_total 1910760
telemt_me_route_drop_channel_closed_total 773
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2016183
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 527
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
telemt_me_writers_active_current 43
telemt_desync_total 9907
telemt_desync_full_logged_total 3072
telemt_desync_suppressed_total 6835
telemt_desync_frames_bucket_total{bucket="1_2"} 2657
telemt_desync_frames_bucket_total{bucket="3_10"} 3714
telemt_desync_frames_bucket_total{bucket="gt_10"} 3536
telemt_pool_swap_total 75
telemt_pool_force_close_total 2276
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 432
telemt_me_draining_writers_reap_progress_total 22845
telemt_me_writer_removed_unexpected_total 419
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1665
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21398
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2229
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20569
telemt_me_writer_teardown_success_total{mode="normal"} 23063
telemt_me_writer_teardown_noop_total 22851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.786709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 432
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 380
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2012854
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 30649816252 (28.54 GB)
telemt_user_octets_to_client{user="hello"} 539799590972 (502.73 GB)
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 81017.5 (22h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3558791
telemt_connections_bad_total 325286
telemt_connections_current 1477
telemt_connections_me_current 1477
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 86063
telemt_upstream_connect_attempt_total 51291
telemt_upstream_connect_success_total 50667
telemt_upstream_connect_fail_total 552
telemt_upstream_connect_attempts_per_request{bucket="1"} 51219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 552
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6013
telemt_me_reconnect_success_total 2184
telemt_me_reader_eof_total 2124
telemt_me_idle_close_by_peer_total 2124
telemt_me_route_drop_no_conn_total 3519856
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2818731
telemt_me_endpoint_quarantine_total 644
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 624
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
telemt_me_writers_active_current 126
telemt_desync_total 10925
telemt_desync_full_logged_total 6082
telemt_desync_suppressed_total 4843
telemt_desync_frames_bucket_total{bucket="1_2"} 2556
telemt_desync_frames_bucket_total{bucket="3_10"} 4300
telemt_desync_frames_bucket_total{bucket="gt_10"} 4069
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 32224
telemt_me_writer_removed_unexpected_total 2080
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30394
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29996
telemt_me_writer_teardown_success_total{mode="normal"} 34309
telemt_me_writer_teardown_noop_total 32224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66533
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.597357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66533
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 1894
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 2830069
telemt_user_connections_current{user="hello"} 1477
telemt_user_octets_from_client{user="hello"} 34716162507 (32.33 GB)
telemt_user_octets_to_client{user="hello"} 622240819126 (579.51 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 861
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 155877.5 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15212733
telemt_connections_bad_total 1404407
telemt_connections_current 2224
telemt_connections_me_current 2224
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 370106
telemt_upstream_connect_attempt_total 70645
telemt_upstream_connect_success_total 70550
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1672
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2610
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1280
telemt_me_idle_close_by_peer_total 1278
telemt_me_route_drop_no_conn_total 13776427
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12166719
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1162
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
telemt_me_writers_active_current 42
telemt_desync_total 49396
telemt_desync_full_logged_total 15500
telemt_desync_suppressed_total 33896
telemt_desync_frames_bucket_total{bucket="1_2"} 11086
telemt_desync_frames_bucket_total{bucket="3_10"} 19304
telemt_desync_frames_bucket_total{bucket="gt_10"} 19006
telemt_pool_swap_total 168
telemt_pool_force_close_total 5691
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 932
telemt_me_draining_writers_reap_progress_total 51281
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47359
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45590
telemt_me_writer_teardown_success_total{mode="normal"} 51822
telemt_me_writer_teardown_noop_total 51331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103153
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 292.901759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103153
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 932
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1151
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 12168014
telemt_user_connections_current{user="hello"} 2224
telemt_user_octets_from_client{user="hello"} 171288555017 (159.52 GB)
telemt_user_octets_to_client{user="hello"} 3134071242315 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 931
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 155878.7 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10975985
telemt_connections_bad_total 1063026
telemt_connections_current 1495
telemt_connections_me_current 1495
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 324910
telemt_upstream_connect_attempt_total 82828
telemt_upstream_connect_success_total 81674
telemt_upstream_connect_fail_total 830
telemt_upstream_connect_attempts_per_request{bucket="1"} 82504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 830
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3909
telemt_me_reconnect_success_total 1590
telemt_me_reader_eof_total 1458
telemt_me_idle_close_by_peer_total 1458
telemt_me_route_drop_no_conn_total 4341544
telemt_me_route_drop_channel_closed_total 477
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8188592
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1178
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36350
telemt_desync_full_logged_total 12216
telemt_desync_suppressed_total 24134
telemt_desync_frames_bucket_total{bucket="1_2"} 8911
telemt_desync_frames_bucket_total{bucket="3_10"} 13998
telemt_desync_frames_bucket_total{bucket="gt_10"} 13441
telemt_pool_swap_total 166
telemt_pool_force_close_total 5128
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 49562
telemt_me_writer_removed_unexpected_total 1489
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44434
telemt_me_writer_teardown_success_total{mode="normal"} 50909
telemt_me_writer_teardown_noop_total 49580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.193809
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8127371
telemt_user_connections_current{user="hello"} 1495
telemt_user_octets_from_client{user="hello"} 203696977925 (189.71 GB)
telemt_user_octets_to_client{user="hello"} 3664318908494 (3.33 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 155843.3 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10392055
telemt_connections_bad_total 893281
telemt_connections_current 1334
telemt_connections_me_current 1334
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 331614
telemt_upstream_connect_attempt_total 68007
telemt_upstream_connect_success_total 67077
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2059
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4638
telemt_me_reconnect_success_total 1864
telemt_me_reader_eof_total 1622
telemt_me_idle_close_by_peer_total 1621
telemt_me_route_drop_no_conn_total 5111926
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7845552
telemt_me_endpoint_quarantine_total 1067
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1144
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 42
telemt_desync_total 35906
telemt_desync_full_logged_total 11893
telemt_desync_suppressed_total 24013
telemt_desync_frames_bucket_total{bucket="1_2"} 9082
telemt_desync_frames_bucket_total{bucket="3_10"} 13727
telemt_desync_frames_bucket_total{bucket="gt_10"} 13097
telemt_pool_swap_total 163
telemt_pool_force_close_total 5077
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 49992
telemt_me_writer_removed_unexpected_total 1762
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5001
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46665
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 539
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44915
telemt_me_writer_teardown_success_total{mode="normal"} 51666
telemt_me_writer_teardown_noop_total 50063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101729
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.154446
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101729
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1615
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 7838610
telemt_user_connections_current{user="hello"} 1334
telemt_user_octets_from_client{user="hello"} 180911266421 (168.49 GB)
telemt_user_octets_to_client{user="hello"} 3257138141653 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 26122.8 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10036345
telemt_connections_bad_total 613561
telemt_connections_current 2186
telemt_connections_me_current 2186
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 176642
telemt_upstream_connect_attempt_total 35004
telemt_upstream_connect_success_total 33245
telemt_upstream_connect_fail_total 1247
telemt_upstream_connect_attempts_per_request{bucket="1"} 34492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1247
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5791
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_route_drop_no_conn_total 24864644
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8360720
telemt_me_endpoint_quarantine_total 164
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 82
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 82
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_me_writers_warm_current 3
telemt_desync_total 12840
telemt_desync_full_logged_total 3282
telemt_desync_suppressed_total 9558
telemt_desync_frames_bucket_total{bucket="1_2"} 2238
telemt_desync_frames_bucket_total{bucket="3_10"} 5227
telemt_desync_frames_bucket_total{bucket="gt_10"} 5375
telemt_pool_swap_total 24
telemt_pool_force_close_total 982
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 7034
telemt_me_writer_removed_unexpected_total 588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6393
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6052
telemt_me_writer_teardown_success_total{mode="normal"} 7586
telemt_me_writer_teardown_noop_total 7039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14625
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.999116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14625
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 8378985
telemt_user_connections_current{user="hello"} 2186
telemt_user_octets_from_client{user="hello"} 57424360786 (53.48 GB)
telemt_user_octets_to_client{user="hello"} 275481702564 (256.56 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 155849.6 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10158211
telemt_connections_bad_total 846560
telemt_connections_current 1873
telemt_connections_me_current 1873
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 224497
telemt_upstream_connect_attempt_total 96751
telemt_upstream_connect_success_total 95765
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 96603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71735
telemt_me_reconnect_success_total 2590
telemt_me_reader_eof_total 2295
telemt_me_idle_close_by_peer_total 2294
telemt_me_route_drop_no_conn_total 5039373
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8014434
telemt_me_endpoint_quarantine_total 1052
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1160
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 41695
telemt_desync_full_logged_total 14225
telemt_desync_suppressed_total 27470
telemt_desync_frames_bucket_total{bucket="1_2"} 8485
telemt_desync_frames_bucket_total{bucket="3_10"} 16133
telemt_desync_frames_bucket_total{bucket="gt_10"} 17077
telemt_pool_swap_total 159
telemt_pool_force_close_total 4709
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 592
telemt_me_draining_writers_reap_progress_total 53073
telemt_me_writer_removed_unexpected_total 2339
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5682
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49750
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 684
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48364
telemt_me_writer_teardown_success_total{mode="normal"} 55432
telemt_me_writer_teardown_noop_total 53074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108506
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.354549
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108506
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 592
telemt_me_refill_failed_total 4264
telemt_me_writer_restored_same_endpoint_total 2177
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 8018458
telemt_user_connections_current{user="hello"} 1873
telemt_user_octets_from_client{user="hello"} 181504301641 (169.04 GB)
telemt_user_octets_to_client{user="hello"} 3017567991492 (2.74 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 706
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 92685.6 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10564555
telemt_connections_bad_total 390867
telemt_connections_current 1492
telemt_connections_me_current 1492
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4456391
telemt_upstream_connect_attempt_total 44738
telemt_upstream_connect_success_total 44412
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 44729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_reconnect_attempts_total 48037
telemt_me_reconnect_success_total 1500
telemt_me_reader_eof_total 1163
telemt_me_idle_close_by_peer_total 1162
telemt_me_route_drop_no_conn_total 3896627
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5058102
telemt_me_endpoint_quarantine_total 603
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 695
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27635
telemt_desync_full_logged_total 9335
telemt_desync_suppressed_total 18300
telemt_desync_frames_bucket_total{bucket="1_2"} 5567
telemt_desync_frames_bucket_total{bucket="3_10"} 10916
telemt_desync_frames_bucket_total{bucket="gt_10"} 11152
telemt_pool_swap_total 97
telemt_pool_force_close_total 3006
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 310
telemt_me_draining_writers_reap_progress_total 31818
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2866
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30208
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2587
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28812
telemt_me_writer_teardown_success_total{mode="normal"} 33074
telemt_me_writer_teardown_noop_total 31825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64899
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.663938
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64899
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 310
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1334
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5051736
telemt_user_connections_current{user="hello"} 1492
telemt_user_octets_from_client{user="hello"} 109006676404 (101.52 GB)
telemt_user_octets_to_client{user="hello"} 1903365094922 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 73656.6 (20h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966003
telemt_connections_bad_total 13544
telemt_connections_current 1122
telemt_connections_me_current 1122
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18621
telemt_upstream_connect_attempt_total 36365
telemt_upstream_connect_success_total 36274
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 36349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 504
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_reconnect_attempts_total 1624
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 331976
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857156
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 610
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4749
telemt_desync_full_logged_total 1452
telemt_desync_suppressed_total 3297
telemt_desync_frames_bucket_total{bucket="1_2"} 1107
telemt_desync_frames_bucket_total{bucket="3_10"} 1886
telemt_desync_frames_bucket_total{bucket="gt_10"} 1756
telemt_pool_swap_total 78
telemt_pool_force_close_total 1966
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 30079
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2321
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28427
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1888
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28113
telemt_me_writer_teardown_success_total{mode="normal"} 30748
telemt_me_writer_teardown_noop_total 30082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60830
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.524440
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60830
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 590
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 858192
telemt_user_connections_current{user="hello"} 1122
telemt_user_octets_from_client{user="hello"} 15505790949 (14.44 GB)
telemt_user_octets_to_client{user="hello"} 385247846871 (358.79 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 155854.0 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12432753
telemt_connections_bad_total 1443618
telemt_connections_current 1967
telemt_connections_me_current 1967
telemt_handshake_timeouts_total 341109
telemt_upstream_connect_attempt_total 58465
telemt_upstream_connect_success_total 58238
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 58415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2268
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1176
telemt_me_idle_close_by_peer_total 1176
telemt_me_route_drop_no_conn_total 4148229
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9396162
telemt_me_endpoint_quarantine_total 1055
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1163
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
telemt_me_writers_active_current 45
telemt_desync_total 38500
telemt_desync_full_logged_total 12574
telemt_desync_suppressed_total 25926
telemt_desync_frames_bucket_total{bucket="1_2"} 9141
telemt_desync_frames_bucket_total{bucket="3_10"} 14266
telemt_desync_frames_bucket_total{bucket="gt_10"} 15093
telemt_pool_swap_total 173
telemt_pool_force_close_total 4758
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 52643
telemt_me_writer_removed_unexpected_total 1130
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49491
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4585
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47885
telemt_me_writer_teardown_success_total{mode="normal"} 53805
telemt_me_writer_teardown_noop_total 52645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106450
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.947360
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106450
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1061
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9365509
telemt_user_connections_current{user="hello"} 1967
telemt_user_octets_from_client{user="hello"} 182652317584 (170.11 GB)
telemt_user_octets_to_client{user="hello"} 4138118303320 (3.76 TB)
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 155850.7 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10777048
telemt_connections_bad_total 1203701
telemt_connections_current 1660
telemt_connections_me_current 1660
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 278086
telemt_upstream_connect_attempt_total 84216
telemt_upstream_connect_success_total 83584
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 84131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_reconnect_attempts_total 8874
telemt_me_reconnect_success_total 2037
telemt_me_reader_eof_total 1903
telemt_me_idle_close_by_peer_total 1903
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5397564
telemt_me_route_drop_channel_closed_total 346
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8329937
telemt_me_endpoint_quarantine_total 1183
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1164
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 38060
telemt_desync_full_logged_total 12299
telemt_desync_suppressed_total 25761
telemt_desync_frames_bucket_total{bucket="1_2"} 9462
telemt_desync_frames_bucket_total{bucket="3_10"} 14190
telemt_desync_frames_bucket_total{bucket="gt_10"} 14408
telemt_pool_swap_total 165
telemt_pool_force_close_total 4603
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 52068
telemt_me_writer_removed_unexpected_total 1929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5411
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48654
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47465
telemt_me_writer_teardown_success_total{mode="normal"} 54065
telemt_me_writer_teardown_noop_total 52073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106138
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.455429
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106138
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1657
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8335988
telemt_user_connections_current{user="hello"} 1660
telemt_user_octets_from_client{user="hello"} 146854639633 (136.77 GB)
telemt_user_octets_to_client{user="hello"} 3181517871855 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 235
```