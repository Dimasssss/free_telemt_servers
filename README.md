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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

## rdp-onedash.ru (2 сервера)
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

# Server Metrics 2026-03-21 12:35:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 57551.8 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1874393
telemt_connections_bad_total 92352
telemt_connections_current 1523
telemt_connections_me_current 1523
telemt_handshake_timeouts_total 70478
telemt_upstream_connect_attempt_total 22295
telemt_upstream_connect_success_total 22185
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 22257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1181
telemt_me_reconnect_success_total 511
telemt_me_reader_eof_total 493
telemt_me_idle_close_by_peer_total 493
telemt_me_route_drop_no_conn_total 1438271
telemt_me_route_drop_channel_closed_total 463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1469957
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 455
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 5662
telemt_desync_full_logged_total 1987
telemt_desync_suppressed_total 3675
telemt_desync_frames_bucket_total{bucket="1_2"} 1220
telemt_desync_frames_bucket_total{bucket="3_10"} 2184
telemt_desync_frames_bucket_total{bucket="gt_10"} 2258
telemt_pool_swap_total 62
telemt_pool_force_close_total 1818
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 19928
telemt_me_writer_removed_unexpected_total 474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1643
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18110
telemt_me_writer_teardown_success_total{mode="normal"} 20254
telemt_me_writer_teardown_noop_total 19932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40186
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 153.434489
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40186
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 444
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1468902
telemt_user_connections_current{user="hello"} 1523
telemt_user_octets_from_client{user="hello"} 21480638943 (20.01 GB)
telemt_user_octets_to_client{user="hello"} 380305489115 (354.19 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3197.2 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223846
telemt_connections_bad_total 14213
telemt_connections_current 1836
telemt_connections_me_current 1836
telemt_handshake_timeouts_total 13512
telemt_upstream_connect_attempt_total 1286
telemt_upstream_connect_success_total 1240
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 88
telemt_me_reconnect_success_total 60
telemt_me_reader_eof_total 57
telemt_me_idle_close_by_peer_total 57
telemt_me_route_drop_no_conn_total 197972
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179914
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
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
telemt_me_writers_active_current 43
telemt_desync_total 658
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 2
telemt_pool_force_close_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 1020
telemt_me_writer_removed_unexpected_total 65
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 136
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 940
telemt_me_writer_teardown_success_total{mode="normal"} 1085
telemt_me_writer_teardown_noop_total 1020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2105
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.204672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2105
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 179827
telemt_user_connections_current{user="hello"} 1836
telemt_user_octets_from_client{user="hello"} 2770619336 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 44026604848 (41.00 GB)
telemt_user_unique_ips_current{user="hello"} 969
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 57549.9 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3601333
telemt_connections_bad_total 373699
telemt_connections_current 3747
telemt_connections_me_current 3747
telemt_handshake_timeouts_total 142233
telemt_upstream_connect_attempt_total 21792
telemt_upstream_connect_success_total 21759
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 811
telemt_me_reconnect_success_total 450
telemt_me_reader_eof_total 459
telemt_me_idle_close_by_peer_total 459
telemt_me_route_drop_no_conn_total 1725158
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2873078
telemt_me_endpoint_quarantine_total 371
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 439
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 12334
telemt_desync_full_logged_total 4162
telemt_desync_suppressed_total 8172
telemt_desync_frames_bucket_total{bucket="1_2"} 2611
telemt_desync_frames_bucket_total{bucket="3_10"} 4835
telemt_desync_frames_bucket_total{bucket="gt_10"} 4888
telemt_pool_swap_total 61
telemt_pool_force_close_total 1926
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 279
telemt_me_draining_writers_reap_progress_total 19799
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1670
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18393
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1785
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17873
telemt_me_writer_teardown_success_total{mode="normal"} 20063
telemt_me_writer_teardown_noop_total 19814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39877
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.446948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39877
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 279
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 406
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2869301
telemt_user_connections_current{user="hello"} 3747
telemt_user_octets_from_client{user="hello"} 46366151352 (43.18 GB)
telemt_user_octets_to_client{user="hello"} 1011086705132 (941.65 GB)
telemt_user_unique_ips_current{user="hello"} 1519
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 57551.1 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2945988
telemt_connections_bad_total 323071
telemt_connections_current 3702
telemt_connections_me_current 3702
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 117178
telemt_upstream_connect_attempt_total 26511
telemt_upstream_connect_success_total 26239
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 26371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 473
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1138
telemt_me_reconnect_success_total 523
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 921027
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2103255
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 440
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
telemt_me_writers_active_current 44
telemt_desync_total 9597
telemt_desync_full_logged_total 3271
telemt_desync_suppressed_total 6326
telemt_desync_frames_bucket_total{bucket="1_2"} 2401
telemt_desync_frames_bucket_total{bucket="3_10"} 3727
telemt_desync_frames_bucket_total{bucket="gt_10"} 3469
telemt_pool_swap_total 62
telemt_pool_force_close_total 1735
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 19311
telemt_me_writer_removed_unexpected_total 473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1630
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18174
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17576
telemt_me_writer_teardown_success_total{mode="normal"} 19804
telemt_me_writer_teardown_noop_total 19312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39116
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.016298
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39116
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2104397
telemt_user_connections_current{user="hello"} 3702
telemt_user_octets_from_client{user="hello"} 39469333549 (36.76 GB)
telemt_user_octets_to_client{user="hello"} 998579182627 (930.00 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 57515.1 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2862830
telemt_connections_bad_total 320256
telemt_connections_current 3332
telemt_connections_me_current 3332
telemt_handshake_timeouts_total 84554
telemt_upstream_connect_attempt_total 23145
telemt_upstream_connect_success_total 23055
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 594
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 866547
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2084619
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 434
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
telemt_desync_total 9688
telemt_desync_full_logged_total 3237
telemt_desync_suppressed_total 6451
telemt_desync_frames_bucket_total{bucket="1_2"} 2522
telemt_desync_frames_bucket_total{bucket="3_10"} 3682
telemt_desync_frames_bucket_total{bucket="gt_10"} 3484
telemt_pool_swap_total 60
telemt_pool_force_close_total 1709
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 189
telemt_me_draining_writers_reap_progress_total 20614
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1710
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1558
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18905
telemt_me_writer_teardown_success_total{mode="normal"} 21170
telemt_me_writer_teardown_noop_total 20618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41788
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.934671
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41788
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 189
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 519
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 2081485
telemt_user_connections_current{user="hello"} 3332
telemt_user_octets_from_client{user="hello"} 47197231056 (43.96 GB)
telemt_user_octets_to_client{user="hello"} 999840493936 (931.17 GB)
telemt_user_unique_ips_current{user="hello"} 1373
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 57554.4 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9453405
telemt_connections_bad_total 651005
telemt_connections_current 5576
telemt_connections_me_current 5576
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 317662
telemt_upstream_connect_attempt_total 88856
telemt_upstream_connect_success_total 83689
telemt_upstream_connect_fail_total 4323
telemt_upstream_connect_attempts_per_request{bucket="1"} 88012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4323
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3480
telemt_me_reconnect_success_total 1176
telemt_me_reader_eof_total 827
telemt_me_idle_close_by_peer_total 826
telemt_me_route_drop_no_conn_total 16928033
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7789725
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 454
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 48
telemt_desync_total 14902
telemt_desync_full_logged_total 4791
telemt_desync_suppressed_total 10111
telemt_desync_frames_bucket_total{bucket="1_2"} 3170
telemt_desync_frames_bucket_total{bucket="3_10"} 6603
telemt_desync_frames_bucket_total{bucket="gt_10"} 5129
telemt_pool_swap_total 58
telemt_pool_force_close_total 1837
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 18840
telemt_me_writer_removed_unexpected_total 1137
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17003
telemt_me_writer_teardown_success_total{mode="normal"} 19859
telemt_me_writer_teardown_noop_total 18849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38708
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.340503
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38708
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 816
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 7847594
telemt_user_connections_current{user="hello"} 5576
telemt_user_octets_from_client{user="hello"} 61720749589 (57.48 GB)
telemt_user_octets_to_client{user="hello"} 685480309204 (638.40 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1924
telemt_user_unique_ips_recent_window{user="hello"} 1042
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 57521.9 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2909687
telemt_connections_bad_total 347837
telemt_connections_current 3651
telemt_connections_me_current 3651
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 63915
telemt_upstream_connect_attempt_total 24730
telemt_upstream_connect_success_total 24458
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 24704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_reconnect_attempts_total 2402
telemt_me_reconnect_success_total 826
telemt_me_reader_eof_total 822
telemt_me_idle_close_by_peer_total 822
telemt_me_route_drop_no_conn_total 1049930
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2198779
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 438
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
telemt_me_writers_active_current 45
telemt_desync_total 10109
telemt_desync_full_logged_total 3559
telemt_desync_suppressed_total 6550
telemt_desync_frames_bucket_total{bucket="1_2"} 1983
telemt_desync_frames_bucket_total{bucket="3_10"} 4048
telemt_desync_frames_bucket_total{bucket="gt_10"} 4078
telemt_pool_swap_total 58
telemt_pool_force_close_total 1630
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 20617
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1964
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19475
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1445
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 185
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18987
telemt_me_writer_teardown_success_total{mode="normal"} 21439
telemt_me_writer_teardown_noop_total 20618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.377129
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2183729
telemt_user_connections_current{user="hello"} 3651
telemt_user_octets_from_client{user="hello"} 40823655092 (38.02 GB)
telemt_user_octets_to_client{user="hello"} 962594673418 (896.49 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1514
telemt_user_unique_ips_recent_window{user="hello"} 527
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 57516.6 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4385592
telemt_connections_bad_total 224701
telemt_connections_current 3088
telemt_connections_me_current 3088
telemt_handshake_timeouts_total 1918897
telemt_upstream_connect_attempt_total 22997
telemt_upstream_connect_success_total 22963
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 902
telemt_me_reconnect_success_total 412
telemt_me_reader_eof_total 417
telemt_me_idle_close_by_peer_total 417
telemt_me_route_drop_no_conn_total 951467
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963669
telemt_me_endpoint_quarantine_total 438
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 450
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
telemt_me_writers_active_current 43
telemt_desync_total 9403
telemt_desync_full_logged_total 3342
telemt_desync_suppressed_total 6061
telemt_desync_frames_bucket_total{bucket="1_2"} 1725
telemt_desync_frames_bucket_total{bucket="3_10"} 3756
telemt_desync_frames_bucket_total{bucket="gt_10"} 3922
telemt_pool_swap_total 62
telemt_pool_force_close_total 1576
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 20575
telemt_me_writer_removed_unexpected_total 401
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1395
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19606
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1523
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18999
telemt_me_writer_teardown_success_total{mode="normal"} 21001
telemt_me_writer_teardown_noop_total 20575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.226025
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1957179
telemt_user_connections_current{user="hello"} 3088
telemt_user_octets_from_client{user="hello"} 35956593172 (33.49 GB)
telemt_user_octets_to_client{user="hello"} 930302244188 (866.41 GB)
telemt_user_unique_ips_current{user="hello"} 1305
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 55507.8 (15h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 921962
telemt_connections_bad_total 88003
telemt_connections_current 726
telemt_connections_me_current 726
telemt_handshake_timeouts_total 330948
telemt_upstream_connect_attempt_total 26357
telemt_upstream_connect_success_total 26355
telemt_upstream_connect_attempts_per_request{bucket="1"} 26355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1118
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 432
telemt_me_route_drop_no_conn_total 194299
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437874
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3025
telemt_desync_full_logged_total 1134
telemt_desync_suppressed_total 1891
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 1079
telemt_desync_frames_bucket_total{bucket="gt_10"} 1422
telemt_pool_swap_total 61
telemt_pool_force_close_total 1368
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 23612
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1720
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22309
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1365
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22244
telemt_me_writer_teardown_success_total{mode="normal"} 24029
telemt_me_writer_teardown_noop_total 23612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.855346
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 353
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 437717
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 6940158435 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 166677646685 (155.23 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 57526.2 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3115954
telemt_connections_bad_total 306554
telemt_connections_current 4320
telemt_connections_me_current 4320
telemt_handshake_timeouts_total 89983
telemt_upstream_connect_attempt_total 23834
telemt_upstream_connect_success_total 23734
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 23803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 969
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 844290
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2447852
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 445
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
telemt_me_writers_active_current 45
telemt_desync_total 9957
telemt_desync_full_logged_total 3271
telemt_desync_suppressed_total 6686
telemt_desync_frames_bucket_total{bucket="1_2"} 2388
telemt_desync_frames_bucket_total{bucket="3_10"} 3713
telemt_desync_frames_bucket_total{bucket="gt_10"} 3856
telemt_pool_swap_total 63
telemt_pool_force_close_total 1597
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 21395
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1652
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20261
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1569
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19798
telemt_me_writer_teardown_success_total{mode="normal"} 21913
telemt_me_writer_teardown_noop_total 21395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.297530
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2440897
telemt_user_connections_current{user="hello"} 4320
telemt_user_octets_from_client{user="hello"} 51691992536 (48.14 GB)
telemt_user_octets_to_client{user="hello"} 1145002852336 (1.04 TB)
telemt_user_unique_ips_current{user="hello"} 1657
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 57522.9 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2814682
telemt_connections_bad_total 235700
telemt_connections_current 3534
telemt_connections_me_current 3534
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 78620
telemt_upstream_connect_attempt_total 39966
telemt_upstream_connect_success_total 39708
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 39922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_reconnect_attempts_total 3409
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 623
telemt_me_idle_close_by_peer_total 623
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 907836
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2260860
telemt_me_endpoint_quarantine_total 499
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 443
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
telemt_me_writers_active_current 45
telemt_desync_total 8700
telemt_desync_full_logged_total 2976
telemt_desync_suppressed_total 5724
telemt_desync_frames_bucket_total{bucket="1_2"} 2242
telemt_desync_frames_bucket_total{bucket="3_10"} 3223
telemt_desync_frames_bucket_total{bucket="gt_10"} 3235
telemt_pool_swap_total 62
telemt_pool_force_close_total 1555
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 20523
telemt_me_writer_removed_unexpected_total 636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19243
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1454
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18968
telemt_me_writer_teardown_success_total{mode="normal"} 21187
telemt_me_writer_teardown_noop_total 20524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.405383
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2271183
telemt_user_connections_current{user="hello"} 3534
telemt_user_octets_from_client{user="hello"} 42457009201 (39.54 GB)
telemt_user_octets_to_client{user="hello"} 995001572824 (926.67 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1369
telemt_user_unique_ips_recent_window{user="hello"} 519
```